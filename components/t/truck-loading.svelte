<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rbd-fe7yh"/><path class="bpwzzk36d"/><rect class="mpjzhb6td"/><circle class="cujvaacjm"/><circle class="g9b4xgbmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:truck-loading" {...props}></Icon>
<style>
:global(.bpwzzk36d) {
  d: path("M13 10.5h5.5m-2.25-2.25l2.25 2.25l-2.25 2.25");
}

:global(.cujvaacjm) {
  cx: 13.5px;
  cy: 18px;
  r: 1.75px;
}

:global(.g9b4xgbmw) {
  cx: 18.5px;
  cy: 18px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mpjzhb6td) {
  width: 4.5px;
  height: 4.5px;
  x: 2.75px;
  y: 8.25px;
  rx: 0.75px;
}

:global(.rbd-fe7yh) {
  width: 11px;
  height: 11.5px;
  x: 10.25px;
  y: 4.75px;
  rx: 1.5px;
}

</style>
