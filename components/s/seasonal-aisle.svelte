<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-gbqsb7e"/><path class="tgtv42nco"/><path class="rx5vjdb4t"/><path class="rzy02ublf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:seasonal-aisle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rx5vjdb4t) {
  d: path("M12 7V4.5q0-1.5 1-2");
}

:global(.rzy02ublf) {
  d: path("M12 5q2.5-2.5 5.5-1.5Q15.5 6 12 5");
}

:global(.tgtv42nco) {
  d: path("M8.5 14a3.5 7 0 1 0 7 0a3.5 7 0 1 0-7 0");
}

:global(.w-gbqsb7e) {
  d: path("M2.5 14a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0");
}

</style>
