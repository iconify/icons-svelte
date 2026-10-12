<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cr-68obad"/><path class="jc2pfdhnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:star-cluster-sharp" {...props}></Icon>
<style>
:global(.cr-68obad) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3q.84 6.16 7 7q-6.16.84-7 7q-.84-6.16-7-7q6.16-.84 7-7Zm7.5 10.25q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Z");
}

:global(.jc2pfdhnu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 5h.01M5.5 19h.01m5.99 1.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
