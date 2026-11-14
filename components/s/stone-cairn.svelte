<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ufipflbct"/><path class="qqzb4qbmy"/><path class="lo-aaohyg"/><path class="y1j4t4bgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stone-cairn" {...props}></Icon>
<style>
:global(.lo-aaohyg) {
  d: path("M7.25 8a4.75 2.25 0 1 0 9.5 0a4.75 2.25 0 1 0-9.5 0Z");
}

:global(.qqzb4qbmy) {
  d: path("M5.5 12.75a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0Z");
}

:global(.ufipflbct) {
  d: path("M3.5 18a8.5 2.75 0 1 0 17 0a8.5 2.75 0 1 0-17 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y1j4t4bgr) {
  d: path("M9 4a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0Z");
}

</style>
