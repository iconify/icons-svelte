<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-t_rcb_j"/><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="pt-3kkb2k"/><path class="ikiprn9sq"/><path class="kdybz_aht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subscription-list-duotone-thin" {...props}></Icon>
<style>
:global(.f-t_rcb_j) {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
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

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.k6fi9qmtq) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.kdybz_aht) {
  d: path("M9 17h6");
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.pt-3kkb2k) {
  d: path("M9 11h6");
}

</style>
