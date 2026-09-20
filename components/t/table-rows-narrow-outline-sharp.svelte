<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0uo3iprf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:table-rows-narrow-outline-sharp" {...props}></Icon>
<style>
:global(.l0uo3iprf) {
  fill: currentColor;
  d: path("M5 15h14v-2H5zm0-4h14V9H5zm0-4h14V5H5zM3 21V3h18v18zm2-2h14v-2H5z");
}

</style>
