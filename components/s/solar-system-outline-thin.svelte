<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bo51iypxr"/><path class="yp6x4sb1k"/><path class="lrlarebcg"/><path class="dxdpz6gbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:solar-system-outline-thin" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dxdpz6gbz) {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lrlarebcg) {
  d: path("M16.5 19.79A9 9 0 1 1 21 12");
}

:global(.yp6x4sb1k) {
  d: path("M18 12a6 6 0 1 1 -3 -5.2");
}

</style>
