<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ib82o_-zw"/><path class="jeawwlbzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-vertical-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ib82o_-zw) {
  stroke-opacity: 0.4;
  d: path("M5 2L5 13M5 22L5 16M12 2L12 10M12 22L12 13M19 2L19 11M19 22L19 14");
}

:global(.jeawwlbzv) {
  d: path("M2 16L8 16M9 10L15 10M16 14L22 14");
}

</style>
