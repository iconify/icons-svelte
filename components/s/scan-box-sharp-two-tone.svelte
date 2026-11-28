<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m-rom16pb"/><path class="b20dyac2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-box-sharp-two-tone" {...props}></Icon>
<style>
:global(.b20dyac2j) {
  d: path("M7 9.4239L12 12M12 12L17 9.4239M12 12L12 17M12 7L17 9.4239L17 14.5761L12 17L7 14.5761L7 9.4239L12 7Z");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.m-rom16pb) {
  stroke-opacity: 0.4;
  d: path("M3 9L3 3L9 3M15 3L21 3L21 9M21 15L21 21L15 21M9 21L3 21L3 15");
}

</style>
