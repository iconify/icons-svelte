<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x-_5ilohg"/><path class="vykqzprfo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-code-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vykqzprfo) {
  d: path("M10.2993 8.1508L7 12L10.2993 15.8492M13.7007 8.1508L17 12L13.7007 15.8492");
}

:global(.x-_5ilohg) {
  d: path("M3 3L21 3L21 21L3 21L3 3Z");
}

</style>
