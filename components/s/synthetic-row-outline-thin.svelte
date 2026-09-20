<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ix782hbkz"/><path class="eylqpv51p"/><path class="ktzvm-xej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:synthetic-row-outline-thin" {...props}></Icon>
<style>
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

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

</style>
