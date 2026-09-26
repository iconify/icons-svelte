<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fbjr9qbyh"/><path class="eal1dfbmd"/><path class="w6vt9xnjt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:signal-high-sharp-two-tone" {...props}></Icon>
<style>
:global(.eal1dfbmd) {
  stroke-opacity: 0.4;
  d: path("M22 21L22 3");
}

:global(.fbjr9qbyh) {
  d: path("M7 21L7 15M12 21L12 11M17 21L17 7");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w6vt9xnjt) {
  fill: currentColor;
  d: path("M1 19L3 19L3 21L1 21Z");
  stroke: none;
}

</style>
