<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fpnv9fnph"/><path class="k7dr3dbje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:strike-zone" {...props}></Icon>
<style>
:global(.fpnv9fnph) {
  d: path("M7 2.5h10v10H7Zm-2.5 13h15V18L12 21.5L4.5 18Z");
}

:global(.k7dr3dbje) {
  d: path("M10 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
