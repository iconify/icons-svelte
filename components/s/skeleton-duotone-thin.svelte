<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v66kzd7uw"/><path class="ceyqjyfpz"/><path class="tacfftb9n"/><path class="fh46dtjbs"/><path class="cj8gecc7a"/><path class="ufjf60bpr"/><path class="cmfydpaql"/><path class="xzo2fg5pj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:skeleton-duotone-thin" {...props}></Icon>
<style>
:global(.ceyqjyfpz) {
  fill: currentColor;
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cj8gecc7a) {
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cmfydpaql) {
  d: path("M10 17v3");
}

:global(.fh46dtjbs) {
  d: path("M5 12a7 7 0 0 1 14 0v3a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tacfftb9n) {
  fill: currentColor;
  d: path("M13 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ufjf60bpr) {
  d: path("M13 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.v66kzd7uw) {
  fill: currentColor;
  d: path("M5 12a7 7 0 0 1 14 0v3a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xzo2fg5pj) {
  d: path("M14 17v3");
}

</style>
