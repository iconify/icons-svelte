<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghdo6iddw"/><path class="w58075boy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:thin-ice-warning" {...props}></Icon>
<style>
:global(.ghdo6iddw) {
  d: path("M15.2 16H2.5L6 4h15.5l-2.24 7.68");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w58075boy) {
  d: path("m12 4l-1.5 4l3 3l-2 5m6.5-1.5V18m0 3h.01");
}

</style>
