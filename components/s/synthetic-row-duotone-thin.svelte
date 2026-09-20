<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mph_12lti"/><path class="x7kl1kqgv"/><path class="qaekcdczc"/><path class="r0_oskb4z"/><path class="epwe3rblo"/><path class="bt_2bvgpa"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ix782hbkz"/><path class="eylqpv51p"/><path class="ktzvm-xej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:synthetic-row-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.epwe3rblo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eylqpv51p) {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ix782hbkz) {
  d: path("M5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.ktzvm-xej) {
  d: path("M17 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.mph_12lti) {
  fill: currentColor;
  d: path("M5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qaekcdczc) {
  fill: currentColor;
  d: path("M17 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r0_oskb4z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.x7kl1kqgv) {
  fill: currentColor;
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
