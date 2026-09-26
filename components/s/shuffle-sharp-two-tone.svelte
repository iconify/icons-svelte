<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i6k0fx_5q"/><path class="jizm28cqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shuffle-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.i6k0fx_5q) {
  stroke-opacity: 0.4;
  d: path("M2 6L8.308 6L10.5316 9.6139M13.4684 14.3861L15.692 18L21 18M17.7071 14.7071L21 18L17.7071 21.2929");
}

:global(.jizm28cqz) {
  d: path("M2 18L8.308 18L15.692 6L21 6M17.7071 2.7071L21 6L17.7071 9.2929");
}

</style>
