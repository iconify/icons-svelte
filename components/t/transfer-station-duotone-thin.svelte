<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x4r46rbgt"/><path class="ior14cbcm"/><path class="zwqs38b8g"/><path class="cqzy_ibpe"/><path class="rw6ho_bav"/><path class="z9ittvbis"/><path class="d4colq8ps"/><path class="l6csbcieq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transfer-station-duotone-thin" {...props}></Icon>
<style>
:global(.cqzy_ibpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 9 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d4colq8ps) {
  d: path("m8 9 4 4 -4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l6csbcieq) {
  d: path("m16 9 -4 4 4 4");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.x4r46rbgt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

:global(.zwqs38b8g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 9 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
