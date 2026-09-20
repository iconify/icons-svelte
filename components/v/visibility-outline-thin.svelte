<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rp243mbkd"/><path class="bo51iypxr"/><path class="rkhcgsbdl"/><path class="irm-6r_xs"/><path class="uzi41e83o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:visibility-outline-thin" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.irm-6r_xs) {
  d: path("M3 17v4");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.rp243mbkd) {
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
}

:global(.uzi41e83o) {
  d: path("M21 17v4");
}

</style>
