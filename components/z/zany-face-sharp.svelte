<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><circle class="qz6997bxv"/><path class="h9hqwcbuo"/><path class="n397k4bjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:zany-face-sharp" {...props}></Icon>
<style>
:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.h9hqwcbuo) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 9.5h.01");
}

:global(.n397k4bjq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 14h8.5m-3.75 0H16v4.25h-3.5V16.5Z");
}

:global(.qz6997bxv) {
  cx: 8.75px;
  cy: 9px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
