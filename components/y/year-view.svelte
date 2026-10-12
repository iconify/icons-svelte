<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jlr8ujb1f"/><path class="kwgxelb8x"/><rect class="szm06ac8e"/><path class="jj_a4-j3e"/><rect class="lck3m1bor"/><path class="y4evliqns"/><rect class="xxsqq7bns"/><path class="p2665_k7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:year-view" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jj_a4-j3e) {
  d: path("M13.75 6h7");
}

:global(.jlr8ujb1f) {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 3.25px;
  rx: 1.75px;
}

:global(.kwgxelb8x) {
  d: path("M3.25 6h7");
}

:global(.lck3m1bor) {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 13.75px;
  rx: 1.75px;
}

:global(.p2665_k7o) {
  d: path("M13.75 16.5h7");
}

:global(.szm06ac8e) {
  width: 7px;
  height: 7px;
  x: 13.75px;
  y: 3.25px;
  rx: 1.75px;
}

:global(.xxsqq7bns) {
  width: 7px;
  height: 7px;
  x: 13.75px;
  y: 13.75px;
  rx: 1.75px;
}

:global(.y4evliqns) {
  d: path("M3.25 16.5h7");
}

</style>
