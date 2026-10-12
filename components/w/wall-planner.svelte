<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="f0ob_2b3h"/><path class="xwaolccwr"/><path class="d7h7k6b1f"/><path class="zjsvsnq6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wall-planner" {...props}></Icon>
<style>
:global(.d7h7k6b1f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 13.25h.01");
}

:global(.f0ob_2b3h) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.xwaolccwr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5h18.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zjsvsnq6j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 13.25h6.25m-11 3.5h11.5");
}

</style>
