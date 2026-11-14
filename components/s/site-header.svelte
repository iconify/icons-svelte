<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="z46iwr9jz"/><path class="zr08r8a0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:site-header" {...props}></Icon>
<style>
:global(.oeucrxbku) {
  d: path("M3.5 2.5h17v19h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z46iwr9jz) {
  fill: currentColor;
  d: path("M3.5 8V4.5a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2V8Z");
}

:global(.zr08r8a0n) {
  d: path("M7 13h10M7 17h6");
}

</style>
