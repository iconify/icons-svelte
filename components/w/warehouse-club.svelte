<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="otzygylmg"/><path class="efo5-ibut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:warehouse-club" {...props}></Icon>
<style>
:global(.efo5-ibut) {
  d: path("M11.2 21.5H5v-8h6.2M5 16h6.2M5 18.5h6.2m-2.7-8.25h7m-1.5 5h8v6.5h-8Zm0 2.25h8");
}

:global(.otzygylmg) {
  d: path("M2.5 21.5V10C6 6 18 6 21.5 10v2.408");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
