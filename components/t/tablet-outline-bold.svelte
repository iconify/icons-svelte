<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d3xn50bni"/><path class="ok9ioqb8x"/><path class="f_bh4os0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tablet-outline-bold" {...props}></Icon>
<style>
:global(.d3xn50bni) {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.f_bh4os0e) {
  d: path("M11 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
