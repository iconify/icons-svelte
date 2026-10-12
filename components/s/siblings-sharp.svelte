<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="x0ddr45xg"/><path class="uyjuswbem"/><circle class="ma8b168go"/><path class="tqelkacwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:siblings-sharp" {...props}></Icon>
<style>
:global(.ma8b168go) {
  cx: 16.5px;
  cy: 12.5px;
  r: 1.5px;
}

:global(.tqelkacwm) {
  d: path("M14 21.25V17.5a2.5 2.5 0 0 1 5 0v3.75Z");
}

:global(.uyjuswbem) {
  d: path("M5.25 21.25V16a2.75 2.75 0 0 1 5.5 0v5.25Z");
}

:global(.x0ddr45xg) {
  cx: 8px;
  cy: 10px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
