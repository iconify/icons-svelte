<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nnzlfsekh"/><path class="x26a8iq1c"/><path class="dpvrwwhil"/><path class="kyzbdrb4r"/><path class="d3d-x8bje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:soft-delete-outline-bold" {...props}></Icon>
<style>
:global(.d3d-x8bje) {
  d: path("m20 14 -4 4");
}

:global(.dpvrwwhil) {
  d: path("M5 9h8");
}

:global(.kyzbdrb4r) {
  d: path("m16 14 4 4");
}

:global(.nnzlfsekh) {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x26a8iq1c) {
  d: path("M2 12h20");
}

</style>
