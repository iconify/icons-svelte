<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nirj1m4jo"/><path class="jmd0hgb9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:widget-map" {...props}></Icon>
<style>
:global(.jmd0hgb9p) {
  d: path("m5.5 12.5l4-1.5l5 1.5l4-1.5v6.5l-4 1.5l-5-1.5l-4 1.5Zm4-1.5v6.5m5-5V19");
}

:global(.nirj1m4jo) {
  d: path("M2.5 2.5h19v19h-19Zm0 6h19M10 4.5h.01m1.99 0h.01m1.99 0h.01M10 6.5h.01m1.99 0h.01m1.99 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
