<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vn6-di86m"/><path class="jjxl5r6ig"/><path class="aq5i5tblx"/><path class="e030h51ix"/><path class="p83l94bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:token-ceiling-outline-bold" {...props}></Icon>
<style>
:global(.aq5i5tblx) {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.e030h51ix) {
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jjxl5r6ig) {
  d: path("M10 11.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.p83l94bht) {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vn6-di86m) {
  d: path("M4 7h16");
}

</style>
