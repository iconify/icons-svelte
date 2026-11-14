<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_xcusb9p"/><path class="vwwitfb8c"/><path class="rxunn00kg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:zoning-map" {...props}></Icon>
<style>
:global(.rxunn00kg) {
  d: path("m5 19l2-2M17 7l2-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vwwitfb8c) {
  fill: currentColor;
  d: path("m2.5 4.5l6-2l3.5 1V12H2.5Z");
}

:global(.x_xcusb9p) {
  d: path("m2.5 4.5l6-2l7 2l6-2v17l-6 2l-7-2l-6 2Zm9.5-1v17M2.5 12h19");
}

</style>
