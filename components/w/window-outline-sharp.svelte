<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu5e7sbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:window-outline-sharp" {...props}></Icon>
<style>
:global(.iu5e7sbjl) {
  fill: currentColor;
  d: path("M21 21H3V3h18zm-8-8v6h6v-6zm0-2h6V5h-6zm-2 0V5H5v6zm0 2H5v6h6z");
}

</style>
