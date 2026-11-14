<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ynda_kb6k"/><path class="lj49l8biv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vulnerable-package" {...props}></Icon>
<style>
:global(.lj49l8biv) {
  d: path("M3.5 6L10 9.5L16.5 6M10 9.5v7m8-1.75v3.5M18 21h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ynda_kb6k) {
  d: path("M10 2.5L16.5 6v7L10 16.5L3.5 13V6Z");
}

</style>
