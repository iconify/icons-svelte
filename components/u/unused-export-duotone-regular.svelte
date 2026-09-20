<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="dx4yo_bup"/><path class="k2pv4cqnd"/><path class="dd2oi04rr"/><path class="kh1n04ogj"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="en0j5saud"/><path class="rkhcgsbdl"/><path class="nk7549ffs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unused-export-duotone-regular" {...props}></Icon>
<style>
:global(.dd2oi04rr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dx4yo_bup) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.en0j5saud) {
  d: path("M3 14h12");
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.k2pv4cqnd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kh1n04ogj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 16.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.nk7549ffs) {
  d: path("m7 16.5 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s1ajs51ib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
