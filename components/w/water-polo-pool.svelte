<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctxb9ubwr"/><path class="bwgo-07ox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-polo-pool" {...props}></Icon>
<style>
:global(.bwgo-07ox) {
  d: path("M2.5 9h3v6h-3m19-6h-3v6h3");
}

:global(.ctxb9ubwr) {
  d: path("M2.5 5h19v14h-19ZM12 5v14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
