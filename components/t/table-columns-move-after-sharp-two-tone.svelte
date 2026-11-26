<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nhjdp-b6l"/><path class="q3lz41b0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-columns-move-after-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nhjdp-b6l) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 3L2 3L2 21L11 21Z");
  stroke: none;
}

:global(.q3lz41b0r) {
  d: path("M20 6L20 3L2 3L2 21L20 21L20 18M11 3L11 21M15 12L22 12M18.7071 8.7071L22 12L18.7071 15.2929");
}

</style>
