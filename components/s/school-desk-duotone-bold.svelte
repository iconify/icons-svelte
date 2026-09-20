<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r9vsub3-y"/><path class="kamdbib6v"/><path class="z_c6v5brq"/><path class="jkzkg9_cz"/><path class="niggb1byh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-desk-duotone-bold" {...props}></Icon>
<style>
:global(.jkzkg9_cz) {
  d: path("M19 7v12");
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.niggb1byh) {
  d: path("M8 10h8v4H8Z");
}

:global(.r9vsub3-y) {
  fill: currentColor;
  d: path("M8 10h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z_c6v5brq) {
  d: path("M5 7v12");
}

</style>
