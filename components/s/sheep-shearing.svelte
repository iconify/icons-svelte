<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uf_m54n0q"/><path class="lvdwsej7t"/><circle class="wft9rcgmo"/><circle class="w8vso_bht"/><path class="mvfj32gkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sheep-shearing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lvdwsej7t) {
  d: path("M5.83 13.76a1.5 2.25 35 1 0-2.46-1.72a1.5 2.25 35 1 0 2.46 1.72m1.42 5.99v1.5m4.5-1.5v1.5");
}

:global(.mvfj32gkh) {
  d: path("M17.4 5.6L9.75 9.5m7.65 1.4L9.75 7");
}

:global(.uf_m54n0q) {
  d: path("M14.5 16.25a1.26 1.26 0 0 1-1.17 1.93a1.76 1.76 0 0 1-2.96 1.02A1.9 1.9 0 0 1 7 18.85a1.51 1.51 0 0 1-2.2-1.57a1.15 1.15 0 0 1 0-2.06A1.51 1.51 0 0 1 7 13.65a1.9 1.9 0 0 1 3.37-.35a1.76 1.76 0 0 1 2.96 1.02a1.26 1.26 0 0 1 1.17 1.93");
}

:global(.w8vso_bht) {
  cx: 19.25px;
  cy: 11.75px;
  r: 2px;
}

:global(.wft9rcgmo) {
  cx: 19.25px;
  cy: 4.75px;
  r: 2px;
}

</style>
