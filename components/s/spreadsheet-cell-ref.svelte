<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8xs3w9gw"/><path class="i5uunab7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spreadsheet-cell-ref" {...props}></Icon>
<style>
:global(.c8xs3w9gw) {
  d: path("M3 3h18v18H3Zm0 6h18M9 3v18");
}

:global(.i5uunab7g) {
  fill: currentColor;
  d: path("M12 12h6v6h-6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
