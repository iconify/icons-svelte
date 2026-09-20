<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x-mvqcbsw"/><path class="xgrfb-bqu"/><path class="t407ddc6o"/><path class="edsmp8bai"/><path class="e2rc7m64w"/><path class="wus2r4r7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-search-duotone-bold" {...props}></Icon>
<style>
:global(.e2rc7m64w) {
  d: path("M13.5 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.edsmp8bai) {
  d: path("M3 18h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t407ddc6o) {
  d: path("M3 12h8");
}

:global(.wus2r4r7n) {
  d: path("m18.5 17 2.5 2.5");
}

:global(.x-mvqcbsw) {
  fill: currentColor;
  d: path("M13.5 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
