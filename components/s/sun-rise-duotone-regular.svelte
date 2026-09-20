<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bwqciab4n"/><path class="mbt4yzbhr"/><path class="u-2slbcxk"/><path class="ilfzlsb9t"/><path class="eu2so4bxo"/><path class="z9ittvbis"/><path class="fd_pyz_no"/><path class="m9_7gnbev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sun-rise-duotone-regular" {...props}></Icon>
<style>
:global(.bwqciab4n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 16a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eu2so4bxo) {
  d: path("M7 16a5 5 0 0 1 10 0");
}

:global(.fd_pyz_no) {
  d: path("M12 5v4");
}

:global(.ilfzlsb9t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 7.5 12 5l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m9_7gnbev) {
  d: path("M9.5 7.5 12 5l2.5 2.5");
}

:global(.mbt4yzbhr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u-2slbcxk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
