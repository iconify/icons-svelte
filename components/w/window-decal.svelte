<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="k2-9s7bzv"/><path class="y0hhkgc7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:window-decal" {...props}></Icon>
<style>
:global(.g6ulkabjn) {
  d: path("M2.5 2.5h19v19h-19Z");
}

:global(.k2-9s7bzv) {
  d: path("M7 7h10v6.5L13.5 17H7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0hhkgc7t) {
  d: path("M17 13.5h-2.5a1 1 0 0 0-1 1V17m-8.75 2.25l1.5-1.5");
}

</style>
