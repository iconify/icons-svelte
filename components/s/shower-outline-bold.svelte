<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wb1hijb7c"/><path class="m74qnacmh"/><path class="qt1fp7i7u"/><path class="nxwi98bwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shower-outline-bold" {...props}></Icon>
<style>
:global(.m74qnacmh) {
  d: path("M4 17a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 8a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.nxwi98bwu) {
  d: path("m15 17.5 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.qt1fp7i7u) {
  d: path("m9 17.5 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wb1hijb7c) {
  d: path("M13.5 5a3.5 3.5 0 0 1 7 0");
}

</style>
