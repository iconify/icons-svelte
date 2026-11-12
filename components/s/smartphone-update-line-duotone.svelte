<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVG6WNJNcPe)" class="caog0qvka"><path class="yncpr3b3n"/><path class="khwr-plop"/><path class="ulu983bfd"/><path class="l0yi6obcv"/></g><defs><clipPath id="SVG6WNJNcPe"><rect class="fng6irbns"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-update-line-duotone" {...props}></Icon>
<style>
:global(.caog0qvka) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.fng6irbns) {
  width: 24px;
  height: 24px;
  fill: var(--svg-color--fff, #fff);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.khwr-plop) {
  stroke-linejoin: round;
  d: path("M2.73016 4.8L2.73016 4C2.73016 1.79086 4.36469 0 6.38098 0C7.47451 0 8.45575 0.526765 9.12484 1.36133M2 4L2.73016 4.8L3.46033 4");
}

:global(.l0yi6obcv) {
  d: path("M15 19H9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ulu983bfd) {
  stroke-linejoin: round;
  d: path("M10.2696 3.2002V4.0002C10.2696 6.20933 8.63507 8.0002 6.61878 8.0002C5.60108 8.0002 4.68065 7.54396 4.01855 6.80798M10.9998 4.0002L10.2696 3.2002L9.53943 4.0002");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.yncpr3b3n) {
  d: path("M13 2.00098C16.1143 2.01009 17.7653 2.10853 18.8284 3.17162C20 4.34319 20 6.22881 20 10V14C20 17.7713 20 19.6569 18.8284 20.8285C17.6569 22 15.7712 22 12 22C8.22876 22 6.34315 22 5.17157 20.8285C4 19.6569 4 17.7713 4 14V11.001");
}

</style>
