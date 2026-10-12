<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="gnq4yvbnv"/><circle class="qkd3rlb4c"/><path class="ahgaes8px"/><path class="gy76-xb2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sponge-sharp" {...props}></Icon>
<style>
:global(.ahgaes8px) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25h18.5v9H2.75zm0 3.25h18.5");
}

:global(.gnq4yvbnv) {
  cx: 7.5px;
  cy: 5.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.gy76-xb2k) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16.5h.01m3.99.25h.01m3.99-.5h.01");
}

:global(.qkd3rlb4c) {
  cx: 12.75px;
  cy: 4.5px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
