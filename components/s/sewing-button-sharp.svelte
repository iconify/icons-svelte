<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="e30mlr4ih"/><path class="z_wb0h3rz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sewing-button-sharp" {...props}></Icon>
<style>
:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.e30mlr4ih) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 12a6.5 6.5 0 1 1-13 0a6.5 6.5 0 1 1 13 0");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.z_wb0h3rz) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10h.01M14 10h.01M10 14h.01M14 14h.01");
}

</style>
