<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hufrlzpcu"/><circle class="bepmk1bhd"/><path class="h3qkj9bop"/><path class="lnxn6ebus"/><path class="rio5yf-5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:turntable" {...props}></Icon>
<style>
:global(.bepmk1bhd) {
  cx: 10px;
  cy: 12px;
  r: 5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.h3qkj9bop) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

:global(.hufrlzpcu) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.lnxn6ebus) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 7v6.5L16 16");
}

:global(.rio5yf-5e) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 7h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
