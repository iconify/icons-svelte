<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6kisabuh"/><path class="vry4dkbrb"/><path class="aj1uncbqw"/><path class="uuhe-zb-s"/><path class="j4po9lbmx"/><path class="oo-1hhwik"/><path class="mb3fb7bkl"/><path class="hepg2-exf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spare-key-duotone-thin" {...props}></Icon>
<style>
:global(.aj1uncbqw) {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hepg2-exf) {
  d: path("M14 16h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4po9lbmx) {
  d: path("M7 16h3");
}

:global(.mb3fb7bkl) {
  d: path("M17 10v10");
}

:global(.oo-1hhwik) {
  d: path("M14 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.t6kisabuh) {
  fill: currentColor;
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uuhe-zb-s) {
  d: path("M7 10v10");
}

:global(.vry4dkbrb) {
  fill: currentColor;
  d: path("M14 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
