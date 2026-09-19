<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u311mcboc"/><path class="liepqlbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shiftmanager-pro" {...props}></Icon>
<style>
:global(.liepqlbbx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.987 23.83l9.25-16.022h6.013L42.5 23.83l-9.25 16.021h-4");
}

:global(.u311mcboc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.256 13.015L20.763 39.851H14.75L5.5 23.83l9.25-16.022h4");
}

</style>
