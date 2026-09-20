<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="epwe3rblo"/><path class="uk8vb-m2y"/><path class="bt_2bvgpa"/><path class="hdist0u2z"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="en0j5saud"/><path class="rkhcgsbdl"/><path class="nk7549ffs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unused-export-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.en0j5saud) {
  d: path("M3 14h12");
}

:global(.epwe3rblo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hdist0u2z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 16.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.nk7549ffs) {
  d: path("m7 16.5 5 -5");
}

:global(.r0_oskb4z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.uk8vb-m2y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
