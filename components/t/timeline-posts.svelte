<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1uw5ib8l"/><circle class="jgyxsrxaa"/><circle class="qcx76zaxv"/><circle class="ufo-xpbwx"/><rect class="ro44wqbuo"/><rect class="ceb1ckbjt"/><rect class="o_qyambzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:timeline-posts" {...props}></Icon>
<style>
:global(.ceb1ckbjt) {
  width: 10.5px;
  height: 4.5px;
  x: 10.75px;
  y: 9.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgyxsrxaa) {
  cx: 6px;
  cy: 5px;
  r: 1.75px;
}

:global(.o_qyambzj) {
  width: 10.5px;
  height: 4.5px;
  x: 10.75px;
  y: 16.75px;
  rx: 1.5px;
}

:global(.qcx76zaxv) {
  cx: 6px;
  cy: 12px;
  r: 1.75px;
}

:global(.ro44wqbuo) {
  width: 10.5px;
  height: 4.5px;
  x: 10.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.ufo-xpbwx) {
  cx: 6px;
  cy: 19px;
  r: 1.75px;
}

:global(.y1uw5ib8l) {
  d: path("M6 6.75v3.5m0 3.5v3.5");
}

</style>
