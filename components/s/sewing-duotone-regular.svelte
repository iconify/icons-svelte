<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n2wmvdxwf"/><path class="tbsb059st"/><path class="gpvq06blh"/><path class="dg-3pj0zi"/><path class="i857i-b1f"/><path class="mzm25fejl"/><path class="m0hvambgh"/><path class="th7wxwuos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sewing-duotone-regular" {...props}></Icon>
<style>
:global(.dg-3pj0zi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gpvq06blh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i857i-b1f) {
  d: path("M4 20 18 6");
}

:global(.m0hvambgh) {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mzm25fejl) {
  d: path("m18 6 3 -3");
}

:global(.n2wmvdxwf) {
  fill: currentColor;
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tbsb059st) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20 18 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.th7wxwuos) {
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
}

</style>
