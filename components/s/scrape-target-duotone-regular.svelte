<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zmp0zuf9j"/><path class="qgk9g7b5k"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f73i47bnv"/><path class="drftkjb-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scrape-target-duotone-regular" {...props}></Icon>
<style>
:global(.drftkjb-q) {
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.f73i47bnv) {
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.qgk9g7b5k) {
  fill: currentColor;
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.zmp0zuf9j) {
  fill: currentColor;
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
