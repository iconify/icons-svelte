<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="inzw2gkjz"/><path class="ypz7skc1v"/><path class="dzt8_kz4w"/><path class="jsnhgcgsv"/><path class="oflx_ndlh"/><path class="rw1qafbrx"/><path class="k_qtzrbjr"/><path class="jlojnsdlu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wifi-duotone-bold" {...props}></Icon>
<style>
:global(.dzt8_kz4w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.86 13.7a7.5 7.5 0 0 1 12.28 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.inzw2gkjz) {
  fill: currentColor;
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jlojnsdlu) {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jsnhgcgsv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.72 15.71a4 4 0 0 1 6.56 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k_qtzrbjr) {
  d: path("M8.72 15.71a4 4 0 0 1 6.56 0");
}

:global(.oflx_ndlh) {
  d: path("M3 11.69a11 11 0 0 1 18 0");
}

:global(.rw1qafbrx) {
  d: path("M5.86 13.7a7.5 7.5 0 0 1 12.28 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ypz7skc1v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11.69a11 11 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
