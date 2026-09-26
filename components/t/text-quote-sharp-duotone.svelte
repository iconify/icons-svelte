<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hrzs9nb5f"/><path class="jjm1ldbgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-quote-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hrzs9nb5f) {
  stroke-opacity: 0.4;
  d: path("M2 5L17 5M6 12L22 12M6 19L22 19");
}

:global(.jjm1ldbgr) {
  d: path("M3 11L3 20");
}

</style>
