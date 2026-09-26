<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="peqarbcox"/><path class="zex-3q21c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trophy-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.peqarbcox) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2L17 2C17.5523 2 18 2.4477 18 3L18 9C18 12.3137 15.3137 15 12 15C8.6863 15 6 12.3137 6 9L6 3C6 2.4477 6.4477 2 7 2Z");
  stroke: none;
}

:global(.zex-3q21c) {
  d: path("M6 2L18 2L18 9C18 12.3137 15.3137 15 12 15C8.6863 15 6 12.3137 6 9L6 2ZM6 5L2 5L2 11L6.3249 11M18 5L22 5L22 11L17.6751 11M12 15L12 19M6 19L18 19L18 22L6 22L6 19Z");
}

</style>
