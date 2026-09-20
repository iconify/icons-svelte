<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oflx_ndlh"/><path class="rw1qafbrx"/><path class="k_qtzrbjr"/><path class="jlojnsdlu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wifi-outline-regular" {...props}></Icon>
<style>
:global(.jlojnsdlu) {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k_qtzrbjr) {
  d: path("M8.72 15.71a4 4 0 0 1 6.56 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oflx_ndlh) {
  d: path("M3 11.69a11 11 0 0 1 18 0");
}

:global(.rw1qafbrx) {
  d: path("M5.86 13.7a7.5 7.5 0 0 1 12.28 0");
}

</style>
