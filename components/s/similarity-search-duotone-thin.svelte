<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aqyofsnqg"/><path class="kf5i1zqrr"/><path class="rencte-ct"/><path class="gzisgqjoz"/><path class="ytlbhsbzy"/><path class="quv6fgbpo"/><path class="oumlmtbql"/><path class="tdux9oy4s"/><path class="idnukobkm"/><path class="jmzox2bbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:similarity-search-duotone-thin" {...props}></Icon>
<style>
:global(.aqyofsnqg) {
  fill: currentColor;
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gzisgqjoz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7.5 11.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.idnukobkm) {
  d: path("m7.5 11.5 3 3");
}

:global(.jmzox2bbn) {
  d: path("m16.5 11.5 -3 3");
}

:global(.kf5i1zqrr) {
  fill: currentColor;
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oumlmtbql) {
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.quv6fgbpo) {
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rencte-ct) {
  fill: currentColor;
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tdux9oy4s) {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ytlbhsbzy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16.5 11.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
