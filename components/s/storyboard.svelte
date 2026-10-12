<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wuf014ltl"/><rect class="qq-shkyyc"/><rect class="tjc_rcb2i"/><rect class="p0s2vccap"/><path class="tiegy7b2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:storyboard" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p0s2vccap) {
  width: 7.5px;
  height: 5px;
  x: 13.5px;
  y: 13px;
  rx: 1.25px;
}

:global(.qq-shkyyc) {
  width: 7.5px;
  height: 5px;
  x: 13.5px;
  y: 4px;
  rx: 1.25px;
}

:global(.tiegy7b2y) {
  d: path("M3 21h4.5m6 0H18");
}

:global(.tjc_rcb2i) {
  width: 7.5px;
  height: 5px;
  x: 3px;
  y: 13px;
  rx: 1.25px;
}

:global(.wuf014ltl) {
  width: 7.5px;
  height: 5px;
  x: 3px;
  y: 4px;
  rx: 1.25px;
}

</style>
