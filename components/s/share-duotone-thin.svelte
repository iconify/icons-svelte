<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgscl2bdj"/><path class="s8txduonj"/><path class="flxcmubzb"/><path class="p_8lzlbte"/><path class="pz7omhb0s"/><path class="zirb-hbnv"/><path class="x8ux9pb9v"/><path class="dvobmj5db"/><path class="otd842a5m"/><path class="x6ykmmben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:share-duotone-thin" {...props}></Icon>
<style>
:global(.dvobmj5db) {
  d: path("M14 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.flxcmubzb) {
  fill: currentColor;
  d: path("M14 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.otd842a5m) {
  d: path("m9.5 10.5 5 -5");
}

:global(.p_8lzlbte) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 10.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pz7omhb0s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 13.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s8txduonj) {
  fill: currentColor;
  d: path("M14 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x6ykmmben) {
  d: path("m9.5 13.5 5 5");
}

:global(.x8ux9pb9v) {
  d: path("M14 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xgscl2bdj) {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zirb-hbnv) {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
