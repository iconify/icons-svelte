<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i9y4kpb3g"/><path class="pnskvqb1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-sample" {...props}></Icon>
<style>
:global(.i9y4kpb3g) {
  d: path("M10 2.5v5.25a7 7 0 1 0 4 0V2.5m-5.5 0h7");
}

:global(.pnskvqb1f) {
  d: path("M5 15c2.5-1.5 4.5 1.5 7 0s4.5 1.5 7 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
