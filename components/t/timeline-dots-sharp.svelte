<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="t09ysxkfx"/><circle class="qcx76zaxv"/><circle class="cq42ivb0d"/><path class="mm8bfyb-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:timeline-dots-sharp" {...props}></Icon>
<style>
:global(.cq42ivb0d) {
  cx: 6px;
  cy: 18.5px;
  r: 1.75px;
}

:global(.mm8bfyb-p) {
  d: path("M6 7.25v3m0 3.5v3M10.5 5.5h9.75m-9.75 13H19M10.5 12h7");
}

:global(.qcx76zaxv) {
  cx: 6px;
  cy: 12px;
  r: 1.75px;
}

:global(.t09ysxkfx) {
  cx: 6px;
  cy: 5.5px;
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
