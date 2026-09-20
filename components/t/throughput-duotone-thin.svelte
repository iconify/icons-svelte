<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovzzbs_1x"/><path class="m8a93sb6x"/><path class="ki9ikb40y"/><path class="qt6bebbgj"/><path class="zuuudpbwi"/><path class="dzvfone4k"/><path class="k134iabcj"/><path class="cks97xg-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:throughput-duotone-thin" {...props}></Icon>
<style>
:global(.cks97xg-s) {
  d: path("m14 13 3 3 -3 3");
}

:global(.dzvfone4k) {
  d: path("m14 5 3 3 -3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k134iabcj) {
  d: path("M3 16h14");
}

:global(.ki9ikb40y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m8a93sb6x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ovzzbs_1x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qt6bebbgj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 13 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zuuudpbwi) {
  d: path("M3 8h14");
}

</style>
