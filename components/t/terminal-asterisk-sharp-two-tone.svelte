<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zzwadwbzf"/><path class="e_3j-yy9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-asterisk-sharp-two-tone" {...props}></Icon>
<style>
:global(.e_3j-yy9k) {
  stroke-opacity: 0.4;
  d: path("M21 19L12 19");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zzwadwbzf) {
  d: path("M8 4.5L8 15.5M3.6 13.3L12.4 6.7M3.6 6.7L12.4 13.3");
}

</style>
