<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srsp9bb6c"/><path class="l18s5p3nb"/><path class="mvxy-gbbs"/><path class="r8sldsvbw"/><path class="lnv5wg3xc"/><path class="rg0uhlb5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:undo-duotone-regular" {...props}></Icon>
<style>
:global(.l18s5p3nb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lnv5wg3xc) {
  d: path("M19 13v5");
}

:global(.mvxy-gbbs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 10 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r8sldsvbw) {
  d: path("M5 13a7 7 0 0 1 14 0");
}

:global(.rg0uhlb5x) {
  d: path("m2 10 3 3 3 -3");
}

:global(.srsp9bb6c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 13a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
