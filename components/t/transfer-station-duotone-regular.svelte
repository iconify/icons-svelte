<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v_dlw1bwz"/><path class="mbt4yzbhr"/><path class="az481cbgr"/><path class="yuc2lmxqb"/><path class="rw6ho_bav"/><path class="z9ittvbis"/><path class="d4colq8ps"/><path class="l6csbcieq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transfer-station-duotone-regular" {...props}></Icon>
<style>
:global(.az481cbgr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 9 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d4colq8ps) {
  d: path("m8 9 4 4 -4 4");
}

:global(.l6csbcieq) {
  d: path("m16 9 -4 4 4 4");
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

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.v_dlw1bwz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yuc2lmxqb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 9 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
