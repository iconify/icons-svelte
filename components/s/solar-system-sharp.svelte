<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ons53cb4g"/><path class="nfgvosgrx"/><circle class="ds98_ox3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:solar-system-sharp" {...props}></Icon>
<style>
:global(.ds98_ox3w) {
  cx: 6.34px;
  cy: 6.34px;
  r: 1.5px;
}

:global(.nfgvosgrx) {
  d: path("M10.34 4.18a8 8 0 1 1-6.16 6.16");
}

:global(.ons53cb4g) {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
