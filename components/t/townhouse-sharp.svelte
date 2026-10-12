<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i17h_kenl"/><path class="fy_3iobof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:townhouse-sharp" {...props}></Icon>
<style>
:global(.fy_3iobof) {
  d: path("M5.88 21.25v-5h3v5M15.13 12h3v3h-3Z");
}

:global(.i17h_kenl) {
  d: path("M2.75 21.25V10.5L7.38 6L12 10.5v-3L16.63 3l4.62 4.5v13.75ZM12 10.5v10.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
