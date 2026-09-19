<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dqi2oo-3i"/><circle class="w7n84kiwk"/><circle class="duy-33kmd"/><circle class="h1rqd2cic"/><path class="jyx0-qbxw"/><circle class="y6iwcxghj"/><circle class="ik_q_qbvk"/><circle class="d-53t3-sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sharex-alt" {...props}></Icon>
<style>
:global(.d-53t3-sh) {
  cx: 15.838px;
  cy: 28.675px;
  r: 0.75px;
  fill: currentColor;
}

:global(.dqi2oo-3i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.878 25.235a9.24 9.24 0 0 1 5.458-9.942m12.78 9.941q.116-.727.116-1.463a9.24 9.24 0 0 0-5.574-8.48m1.692 16.013a9.24 9.24 0 0 1-10.695.003");
}

:global(.duy-33kmd) {
  cx: 15.838px;
  cy: 28.64px;
  r: 3.495px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.h1rqd2cic) {
  cx: 32.161px;
  cy: 28.675px;
  r: 3.495px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ik_q_qbvk) {
  cx: 32.161px;
  cy: 28.675px;
  r: 0.75px;
  fill: currentColor;
}

:global(.jyx0-qbxw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.754 34.25v-20.5L24 3.5L6.247 13.75v20.5L24 44.5z");
}

:global(.w7n84kiwk) {
  cx: 24.024px;
  cy: 14.483px;
  r: 3.495px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y6iwcxghj) {
  cx: 24px;
  cy: 14.483px;
  r: 0.75px;
  fill: currentColor;
}

</style>
