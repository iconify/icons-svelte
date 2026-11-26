<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="clzz43bhf"/><path class="tb3n6mbjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:squares-intersect-sharp-two-tone" {...props}></Icon>
<style>
:global(.clzz43bhf) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 8L15 8C15.5523 8 16 8.4477 16 9L16 15C16 15.5523 15.5523 16 15 16L9 16C8.4477 16 8 15.5523 8 15L8 9C8 8.4477 8.4477 8 9 8Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tb3n6mbjz) {
  d: path("M9 9L15 9L15 15L9 15ZM6 15L3 15L3 10.5M3 7.5L3 3L7.5 3M10.5 3L15 3L15 6M18 9L21 9L21 13.5M21 16.5L21 21L16.5 21M13.5 21L9 21L9 18");
}

</style>
