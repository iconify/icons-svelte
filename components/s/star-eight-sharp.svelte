<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ad74glq6d"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:star-eight-sharp" {...props}></Icon>
<style>
:global(.ad74glq6d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.41 3.2l1.38 2.69l.41.8l.86-.28l2.87-.92l.86-.28l-.28.86l-.92 2.87l-.28.86l.8.41l2.69 1.38l.8.41l-.8.41l-2.69 1.38l-.8.41l.28.86l.92 2.87l.28.86l-.86-.28l-2.87-.92l-.86-.28l-.41.8l-1.38 2.69l-.41.8l-.41-.8l-1.38-2.69l-.41-.8l-.86.28l-2.87.92l-.86.28l.28-.86l.92-2.87l.28-.86l-.8-.41l-2.69-1.38l-.8-.41l.8-.41l2.69-1.38l.8-.41l-.28-.86l-.92-2.87l-.28-.86l.86.28l2.87.92l.86.28l.41-.8l1.38-2.69l.41-.8z");
}

:global(.to8m3ibcr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
