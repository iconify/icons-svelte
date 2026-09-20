<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="kllnjy40b"/><path class="n8j0mqbjg"/><path class="mgnx0cbow"/><path class="bo51iypxr"/><path class="yp6x4sb1k"/><path class="lrlarebcg"/><path class="dxdpz6gbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:solar-system-duotone-regular" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dxdpz6gbz) {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.kllnjy40b) {
  fill: currentColor;
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lrlarebcg) {
  d: path("M16.5 19.79A9 9 0 1 1 21 12");
}

:global(.mgnx0cbow) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 19.79A9 9 0 1 1 21 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n8j0mqbjg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12a6 6 0 1 1 -3 -5.2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yp6x4sb1k) {
  d: path("M18 12a6 6 0 1 1 -3 -5.2");
}

</style>
