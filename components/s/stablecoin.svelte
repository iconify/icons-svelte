<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vzrb_jbrn"/><path class="vyzbnkbbf"/><path class="zr9bgyb0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stablecoin" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vyzbnkbbf) {
  d: path("M2.5 9v3a4 2.5 0 0 0 8 0V9m3 0a4 2.5 0 1 0 8 0a4 2.5 0 1 0-8 0Z");
}

:global(.vzrb_jbrn) {
  d: path("M2.5 9a4 2.5 0 1 0 8 0a4 2.5 0 1 0-8 0Z");
}

:global(.zr9bgyb0d) {
  d: path("M13.5 9v3a4 2.5 0 0 0 8 0V9m-19 8.5h19");
}

</style>
