<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nm008x03r"/><circle class="juap84dhf"/><path class="ffzadgbho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:step-into-sharp" {...props}></Icon>
<style>
:global(.ffzadgbho) {
  d: path("M3.75 18.25h3.5m9.5 0h3.5");
}

:global(.juap84dhf) {
  cx: 12px;
  cy: 18.25px;
  r: 2.25px;
}

:global(.nm008x03r) {
  d: path("M5 12.5a7 7 0 0 1 14 0m-2.25-2.25L19 12.5l2.25-2.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
