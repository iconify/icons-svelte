<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fhgfjmnof"/><path class="x216ecbyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:treasury-covenant" {...props}></Icon>
<style>
:global(.fhgfjmnof) {
  d: path("M3.5 2.5h15v4h-15Zm2 4v15h6.7m4.3-9.3V6.5m-8 4h5m-5 3.5h3.7m2.8 1h6v6h-6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x216ecbyc) {
  d: path("m16.5 18l1 1l2-2");
}

</style>
