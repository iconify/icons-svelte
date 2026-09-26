<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="pxe2_ubmz"/><path class="e5xtnl27s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:siren-sharp-fill" {...props}></Icon>
<style>
:global(.e5xtnl27s) {
  d: path("M5.9289 6.9289L4.636 5.636M12 5L12 2M18.0711 6.9289L19.364 5.636");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pxe2_ubmz) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 16L6 13C6 9.6863 8.6863 7 12 7C15.3137 7 18 9.6863 18 13L18 16L20 16C20.5523 16 21 16.4477 21 17L21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 17C3 16.4477 3.4477 16 4 16L6 16ZM5 18L5 20L19 20L19 18L5 18Z");
  stroke: none;
}

</style>
