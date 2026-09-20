<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfzmy-bgb"/><path class="gcurcebny"/><path class="faqh69b5q"/><path class="qc36m6bjs"/><path class="i2wbmzb2w"/><path class="o37zm_b2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sun-weather-duotone-thin" {...props}></Icon>
<style>
:global(.faqh69b5q) {
  d: path("M3.5 3.5 6 6");
}

:global(.gcurcebny) {
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.gfzmy-bgb) {
  fill: currentColor;
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
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

:global(.i2wbmzb2w) {
  d: path("M3.5 20.5 6 18");
}

:global(.o37zm_b2b) {
  d: path("M20.5 20.5 18 18");
}

:global(.qc36m6bjs) {
  d: path("M20.5 3.5 18 6");
}

</style>
