<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nzpsuduik"/><path class="cl924fb_o"/><path class="bd3-a5q0s"/><path class="t-3b9ybzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:texture-gen-outline-bold" {...props}></Icon>
<style>
:global(.bd3-a5q0s) {
  d: path("M6 18 18 6");
}

:global(.cl924fb_o) {
  d: path("m6 12 6 -6");
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t-3b9ybzs) {
  d: path("m12 18 6 -6");
}

</style>
