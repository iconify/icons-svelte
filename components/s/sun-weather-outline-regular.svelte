<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gcurcebny"/><path class="faqh69b5q"/><path class="qc36m6bjs"/><path class="i2wbmzb2w"/><path class="o37zm_b2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sun-weather-outline-regular" {...props}></Icon>
<style>
:global(.faqh69b5q) {
  d: path("M3.5 3.5 6 6");
}

:global(.gcurcebny) {
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.i2wbmzb2w) {
  d: path("M3.5 20.5 6 18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o37zm_b2b) {
  d: path("M20.5 20.5 18 18");
}

:global(.qc36m6bjs) {
  d: path("M20.5 3.5 18 6");
}

</style>
