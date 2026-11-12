<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lghfbwbad"/><path class="f_ilzosws"/><path class="lqfqjbb0r"/><path class="ppqxdzqbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-from-bottom-to-top-linear" {...props}></Icon>
<style>
:global(.f_ilzosws) {
  d: path("M6 13H13");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lghfbwbad) {
  d: path("M4 8H13");
}

:global(.lqfqjbb0r) {
  d: path("M8 18H13");
}

:global(.ppqxdzqbu) {
  stroke-linejoin: round;
  d: path("M17 20V4L20 8");
}

</style>
