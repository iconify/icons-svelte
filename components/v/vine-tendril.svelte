<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o42i3wbot"/><path class="qdzi1s4_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vine-tendril" {...props}></Icon>
<style>
:global(.o42i3wbot) {
  d: path("M3.5 21.5C3.5 13 8 4 14 4a5.5 5.5 0 0 1 0 11a3.5 3.5 0 0 1 0-7a2 2 0 0 1 0 4");
}

:global(.qdzi1s4_k) {
  d: path("M4 16.5c2-2 4.5-1.5 6 1c-2.5 1.5-4.5 1-6-1Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
