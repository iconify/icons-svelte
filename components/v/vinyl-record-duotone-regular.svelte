<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a8v2s5z3p"/><path class="gbt-66b2v"/><path class="cxoq7xbon"/><path class="vrj8akbcc"/><path class="bxyh6cbnl"/><path class="ync9d6bsc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vinyl-record-duotone-regular" {...props}></Icon>
<style>
:global(.a8v2s5z3p) {
  fill: currentColor;
  d: path("M3 4v16h14V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.bxyh6cbnl) {
  d: path("M9 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.cxoq7xbon) {
  fill: currentColor;
  d: path("M14 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gbt-66b2v) {
  fill: currentColor;
  d: path("M9 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vrj8akbcc) {
  d: path("M3 4v16h14V4Z");
}

:global(.ync9d6bsc) {
  d: path("M14 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
