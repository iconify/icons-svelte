<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o9_okin1f"/><path class="j5e8npbes"/><path class="ra4u4oiby"/><circle class="byu9zgdxu"/><path class="eonjggvry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-by-time-line-duotone" {...props}></Icon>
<style>
:global(.byu9zgdxu) {
  cx: 17px;
  cy: 12px;
  r: 5px;
}

:global(.eonjggvry) {
  stroke-linejoin: round;
  d: path("M17 10V11.8462L18 13");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j5e8npbes) {
  d: path("M8 12H2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.o9_okin1f) {
  d: path("M10 7L2 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ra4u4oiby) {
  d: path("M10 17H2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
