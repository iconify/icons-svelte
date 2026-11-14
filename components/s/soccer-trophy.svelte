<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yyr_egbab"/><path class="yb_llpbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:soccer-trophy" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yb_llpbyl) {
  d: path("M7 5H4.5c0 4 1.5 5.5 3.25 6.5M17 5h2.5c0 4-1.5 5.5-3.25 6.5");
}

:global(.yyr_egbab) {
  d: path("M7 3.5h10V9A5 5 0 0 1 7 9ZM12 14v3.5m-4 0h8V21H8Z");
}

</style>
