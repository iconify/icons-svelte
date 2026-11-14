<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="knk109_hl"/><path class="q58l7it0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:traffic-light-amber" {...props}></Icon>
<style>
:global(.knk109_hl) {
  d: path("M7.5 2h9v20h-9ZM12 6h.01");
}

:global(.q58l7it0y) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 6h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
