<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rb_yrwbfa"/><path class="rg7pmxk_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-off-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.rb_yrwbfa) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m0 10h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8");
}

:global(.rg7pmxk_j) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10H6a3 3 0 0 1-3-3c0-1.085.138-2.473 1-3m6 0h8a3 3 0 0 1 0 6h-2m4 10c-.455.278-1.428 0-2 0H6a3 3 0 0 1 0-6h8m-7 3h.01M2 2l20 20");
}

</style>
