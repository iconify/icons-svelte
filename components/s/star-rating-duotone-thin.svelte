<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ke9vtlmtz"/><path class="fgk90dbkb"/><path class="e3yycdcdm"/><path class="hufxdfd1k"/><path class="x7bkced7s"/><path class="nesq7qlnx"/><path class="u4sowhi7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:star-rating-duotone-thin" {...props}></Icon>
<style>
:global(.e3yycdcdm) {
  fill: currentColor;
  d: path("m17.5 8 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fgk90dbkb) {
  fill: currentColor;
  d: path("m12 8 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hufxdfd1k) {
  d: path("m6.5 8 2 2 -2 2 -2 -2Z");
}

:global(.ke9vtlmtz) {
  fill: currentColor;
  d: path("m6.5 8 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nesq7qlnx) {
  d: path("m17.5 8 2 2 -2 2 -2 -2Z");
}

:global(.u4sowhi7h) {
  d: path("M4 16h16");
}

:global(.x7bkced7s) {
  d: path("m12 8 2 2 -2 2 -2 -2Z");
}

</style>
