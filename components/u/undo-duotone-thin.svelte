<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dlo9y2ukg"/><path class="tbjpgc12z"/><path class="ukg6gk7fi"/><path class="r8sldsvbw"/><path class="lnv5wg3xc"/><path class="rg0uhlb5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:undo-duotone-thin" {...props}></Icon>
<style>
:global(.dlo9y2ukg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 13a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lnv5wg3xc) {
  d: path("M19 13v5");
}

:global(.r8sldsvbw) {
  d: path("M5 13a7 7 0 0 1 14 0");
}

:global(.rg0uhlb5x) {
  d: path("m2 10 3 3 3 -3");
}

:global(.tbjpgc12z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ukg6gk7fi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 10 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
