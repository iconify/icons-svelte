<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dl_n0-bws"/><path class="do5x66b_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-in-down-left-sharp-duotone" {...props}></Icon>
<style>
:global(.dl_n0-bws) {
  stroke-opacity: 0.4;
  d: path("M10 7L3 7L3 21L17 21L17 14");
}

:global(.do5x66b_h) {
  d: path("M21.2929 2.7071L13.1464 10.8536M22 11L13 11L13 2");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
