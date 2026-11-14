<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwk9ecb2i"/><path class="j0977jdqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:table-cells-split" {...props}></Icon>
<style>
:global(.j0977jdqt) {
  d: path("m7.5 10l-2 2l2 2m7.5-2h3.5m-2-2l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uwk9ecb2i) {
  d: path("M2.5 5h19v14h-19ZM12 5v14m-3-7H5.5");
}

</style>
