<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuy7pwb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:store-outline-sharp" {...props}></Icon>
<style>
:global(.xuy7pwb0u) {
  fill: currentColor;
  d: path("M4 6V4h16v2zm0 14v-6H3v-2l1-5h16l1 5v2h-1v6h-2v-6h-4v6zm2-2h6v-4H6zm-.95-6h13.9zm0 0h13.9l-.6-3H5.65z");
}

</style>
