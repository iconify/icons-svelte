<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lghfbwbad"/><path class="pnx-7hdbe"/><path class="r-fwg-bgp"/><path class="ppqxdzqbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-from-bottom-to-top-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lghfbwbad) {
  d: path("M4 8H13");
}

:global(.pnx-7hdbe) {
  d: path("M6 13H13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ppqxdzqbu) {
  stroke-linejoin: round;
  d: path("M17 20V4L20 8");
}

:global(.r-fwg-bgp) {
  d: path("M8 18H13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
