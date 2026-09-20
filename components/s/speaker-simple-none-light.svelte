<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="crb_862ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:speaker-simple-none-light" {...props}></Icon>
<style>
:global(.crb_862ev) {
  fill: currentColor;
  d: path("M162.64 26.61a6 6 0 0 0-6.32.65L85.94 82H40a14 14 0 0 0-14 14v64a14 14 0 0 0 14 14h45.94l70.38 54.74A6 6 0 0 0 166 224V32a6 6 0 0 0-3.36-5.39M154 211.73l-62.32-48.47A6 6 0 0 0 88 162H40a2 2 0 0 1-2-2V96a2 2 0 0 1 2-2h48a6 6 0 0 0 3.68-1.26L154 44.27Z");
}

</style>
