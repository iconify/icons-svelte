<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g7d56fjnv"/><path class="u58t-7r9s"/><path class="vo_w1yb4j"/><path class="vyks9vbfn"/><path class="i2unvmb0b"/><path class="epb14lb-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-timetable-duotone-bold" {...props}></Icon>
<style>
:global(.epb14lb-b) {
  d: path("M13 13h6v4h-6Z");
}

:global(.g7d56fjnv) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.i2unvmb0b) {
  d: path("M5 8h6v4H5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u58t-7r9s) {
  fill: currentColor;
  d: path("M5 8h6v4H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vo_w1yb4j) {
  fill: currentColor;
  d: path("M13 13h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
