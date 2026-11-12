<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ko3tfdb4i"/><path class="i6nrt8nnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:women-line-duotone" {...props}></Icon>
<style>
:global(.i6nrt8nnu) {
  d: path("M19 9C19 12.866 15.866 16 12 16C8.13401 16 5 12.866 5 9C5 5.13401 8.13401 2 12 2C15.866 2 19 5.13401 19 9Z");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ko3tfdb4i) {
  stroke-linejoin: round;
  d: path("M11.9997 16V18.5M11.9997 18.5H9.5M11.9997 18.5H14.5M11.9997 18.5L12 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
