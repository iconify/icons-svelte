<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="l6cd208_p"/><path class="v625axawh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:token-transit" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.l6cd208_p) {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v625axawh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.666 28.94V13.783h6.876H11.79m17.551 23.916V22.542h6.876h-13.753");
}

</style>
