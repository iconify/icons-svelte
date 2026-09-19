<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="vsjvu9l7d"/><path class="xculwvxug"/><circle class="h8uw6qbuj"/><path class="u0sg0zbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:time-recording-pro" {...props}></Icon>
<style>
:global(.h8uw6qbuj) {
  cx: 24px;
  cy: 27.353px;
  r: 10.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u0sg0zbnb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.578V19.86m4.26 7.493h-5.485");
}

:global(.vsjvu9l7d) {
  width: 37px;
  height: 34.32px;
  x: 5.5px;
  y: 6.84px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.xculwvxug) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.357 16.253v-5.978m-5.685 2.989H42.5m-5.686-2.989v5.978");
}

</style>
