<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u4c4gab6p"/><path class="t7x-z5m1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:souvenir" {...props}></Icon>
<style>
:global(.t7x-z5m1d) {
  d: path("m12 7l-3.75 6h7.5Zm0 6v2.5");
}

:global(.u4c4gab6p) {
  d: path("M6 15.5a7.5 7.5 0 1 1 12 0m-13.5 0h15L21 21H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
