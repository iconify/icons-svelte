<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="y70lhiizb"/><path class="r0u1p1gdv"/><path class="j98an1bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vipps" {...props}></Icon>
<style>
:global(.j98an1bqd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

:global(.r0u1p1gdv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.083 23.803c5.977 8.485 14.174 11.149 21.577 1.15");
}

:global(.y70lhiizb) {
  cx: 28.304px;
  cy: 16.948px;
  r: 0.75px;
  fill: currentColor;
}

</style>
