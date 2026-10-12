<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rlkyj_bwb"/><circle class="dpu0-e8pd"/><circle class="w2fp3ub6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:text-select-sharp" {...props}></Icon>
<style>
:global(.dpu0-e8pd) {
  cx: 6px;
  cy: 7.25px;
  r: 1.25px;
}

:global(.rlkyj_bwb) {
  d: path("M3.75 3.75h16.5m-16.5 16.5h10M9 8.75h6v6.5H9zM11 12h2M6 8.5v6.75m12-6.5v6.75");
}

:global(.w2fp3ub6f) {
  cx: 18px;
  cy: 16.75px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
