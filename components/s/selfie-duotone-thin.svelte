<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyhe1mbtf"/><path class="ke6n18qno"/><path class="d269etb2f"/><path class="iu1vklb-k"/><path class="rrvudvrpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:selfie-duotone-thin" {...props}></Icon>
<style>
:global(.d269etb2f) {
  d: path("M6 3v14h10V3Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu1vklb-k) {
  d: path("M9 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ke6n18qno) {
  fill: currentColor;
  d: path("M9 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rrvudvrpy) {
  d: path("m16 15 4 4v3");
}

:global(.yyhe1mbtf) {
  fill: currentColor;
  d: path("M6 3v14h10V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
