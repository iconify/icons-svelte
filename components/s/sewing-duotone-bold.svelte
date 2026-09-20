<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n2wmvdxwf"/><path class="a0ikyhbck"/><path class="f2ie39jzc"/><path class="j3n3f_mcr"/><path class="i857i-b1f"/><path class="mzm25fejl"/><path class="m0hvambgh"/><path class="th7wxwuos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sewing-duotone-bold" {...props}></Icon>
<style>
:global(.a0ikyhbck) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20 18 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f2ie39jzc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i857i-b1f) {
  d: path("M4 20 18 6");
}

:global(.j3n3f_mcr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m0hvambgh) {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mzm25fejl) {
  d: path("m18 6 3 -3");
}

:global(.n2wmvdxwf) {
  fill: currentColor;
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.th7wxwuos) {
  d: path("M4 12c3 -3 5 3 8 0s5 3 8 0");
}

</style>
