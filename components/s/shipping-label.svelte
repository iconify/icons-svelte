<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qzkvbx_uy"/><path class="ji9zu2beh"/><rect class="j7g0efbou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shipping-label" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7g0efbou) {
  width: 4px;
  height: 4px;
  x: 14.25px;
  y: 7.25px;
  rx: 0.75px;
}

:global(.ji9zu2beh) {
  d: path("M5.75 8.25h5.5m-5.5 3h3.5m-3.5 4h12.5");
}

:global(.qzkvbx_uy) {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

</style>
