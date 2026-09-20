<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t52bbg2ls"/><path class="fcpcpjxqg"/><path class="cf-uvg73o"/><path class="fi51gbcse"/><path class="heav9sszs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unlock-duotone-thin" {...props}></Icon>
<style>
:global(.cf-uvg73o) {
  d: path("M5 11a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.fcpcpjxqg) {
  fill: currentColor;
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fi51gbcse) {
  d: path("M7 9a5 5 0 0 1 8.54 -3.54");
}

:global(.heav9sszs) {
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t52bbg2ls) {
  fill: currentColor;
  d: path("M5 11a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
