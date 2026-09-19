<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="gkgmxyejw"/><path class="zbdsahbsq"/><circle class="r0ic7tgjc"/><path class="clbsi56li"/><circle class="q2k9mvbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sulamericasaude" {...props}></Icon>
<style>
:global(.clbsi56li) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.47 25.87h3.1a3.11 3.11 0 0 0 3.1-2.82l1.08-11.56a4.58 4.58 0 0 0-2.31-4.41l-.1-.08");
}

:global(.gkgmxyejw) {
  cx: 35.02px;
  cy: 22.81px;
  r: 4.81px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q2k9mvbzs) {
  cx: 18.5px;
  cy: 6.44px;
  r: 1.94px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r0ic7tgjc) {
  cx: 12.44px;
  cy: 6.44px;
  r: 1.94px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zbdsahbsq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.47 24.73v9a9.8 9.8 0 0 0 19.6 0v-6.11m-19.6-1.75h-3.1a3.11 3.11 0 0 1-3.09-2.82L8.19 11.49a4.59 4.59 0 0 1 2.31-4.41l.1-.08");
}

</style>
