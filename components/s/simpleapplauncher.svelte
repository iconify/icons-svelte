<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ju28bbctx"/><circle class="u91atmj0i"/><circle class="lzd67abzj"/><circle class="d1bmhbmcn"/><circle class="d8dow8jnh"/><circle class="t_o5q7bvk"/><circle class="okavaj3da"/><circle class="fqdx14vii"/><circle class="dqrnerqbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:simpleapplauncher" {...props}></Icon>
<style>
:global(.d1bmhbmcn) {
  cx: 10.64px;
  cy: 24px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.d8dow8jnh) {
  cx: 24px;
  cy: 24px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dqrnerqbn) {
  cx: 37.36px;
  cy: 37.36px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.fqdx14vii) {
  cx: 24px;
  cy: 37.36px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ju28bbctx) {
  cx: 10.64px;
  cy: 10.64px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lzd67abzj) {
  cx: 37.36px;
  cy: 10.64px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.okavaj3da) {
  cx: 10.64px;
  cy: 37.36px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.t_o5q7bvk) {
  cx: 37.36px;
  cy: 24px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u91atmj0i) {
  cx: 24px;
  cy: 10.64px;
  r: 5.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
