<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7h8iyqlm"/><path class="j53em0blo"/><path class="mwg4tx1bf"/><path class="g49zezblv"/><path class="nf9lhr60h"/><path class="x8_s66bwx"/><path class="k4qo1xe9v"/><path class="rjl8fe1sw"/><path class="ed-cudrmv"/><path class="i7797vbcv"/><path class="gzw9grb_d"/><path class="c4khiwgvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-playground-duotone-thin" {...props}></Icon>
<style>
:global(.b7h8iyqlm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.ed-cudrmv) {
  d: path("M20 6v14");
}

:global(.g49zezblv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 6v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gzw9grb_d) {
  d: path("M15 6v9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7797vbcv) {
  d: path("M9 6v9");
}

:global(.j53em0blo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k4qo1xe9v) {
  d: path("M4 6h16");
}

:global(.mwg4tx1bf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nf9lhr60h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 6v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rjl8fe1sw) {
  d: path("M4 6v14");
}

:global(.x8_s66bwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
