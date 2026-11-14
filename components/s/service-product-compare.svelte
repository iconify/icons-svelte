<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mcxhr7b1o"/><path class="ir1-6pcpj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:service-product-compare" {...props}></Icon>
<style>
:global(.ir1-6pcpj) {
  d: path("m5.25 12l2 2l2.5-4m5 2h3.5");
}

:global(.mcxhr7b1o) {
  d: path("M3 3.5h18v17H3Zm9 0v17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
