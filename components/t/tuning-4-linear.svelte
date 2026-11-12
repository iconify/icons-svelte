<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><circle class="o9b-osuxb"/><circle class="mrtq9bbsf"/><path class="m--2_4b9i"/><path class="c132ob09n"/><path class="k1zry6b1k"/><path class="pmm8k_1gb"/><path class="djqcecb9b"/><path class="ll27y-b5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tuning-4-linear" {...props}></Icon>
<style>
:global(.c132ob09n) {
  d: path("M14 20L19 20");
}

:global(.djqcecb9b) {
  d: path("M5 20L6 20");
}

:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k1zry6b1k) {
  d: path("M10 4L5 4");
}

:global(.ll27y-b5e) {
  d: path("M19 4L18 4");
}

:global(.m--2_4b9i) {
  d: path("M16 12L19 12");
}

:global(.mrtq9bbsf) {
  cx: 14px;
  cy: 4px;
  r: 2px;
}

:global(.o9b-osuxb) {
  cx: 10px;
  cy: 20px;
  r: 2px;
}

:global(.pmm8k_1gb) {
  d: path("M5 12L8 12");
}

</style>
