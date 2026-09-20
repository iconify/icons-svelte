<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a0f0f2w0j"/><path class="lmnp7qbpj"/><path class="s47awcc6i"/><path class="jfhg8zbol"/><path class="aig5gcc6s"/><path class="me177l4bh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sli-duotone-regular" {...props}></Icon>
<style>
:global(.a0f0f2w0j) {
  fill: currentColor;
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.aig5gcc6s) {
  d: path("m12 17 5 -5");
}

:global(.jfhg8zbol) {
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
}

:global(.lmnp7qbpj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.me177l4bh) {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s47awcc6i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 17 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
