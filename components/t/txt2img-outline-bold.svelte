<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f1vpicczb"/><path class="o0-3vqblf"/><path class="gyvfay9gb"/><path class="rns28-8pl"/><path class="kkozh6bab"/><path class="e46qmbbbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:txt2img-outline-bold" {...props}></Icon>
<style>
:global(.e46qmbbbk) {
  d: path("m14 19 2.5 -2.5L19 19");
}

:global(.f1vpicczb) {
  d: path("M2 4h8");
}

:global(.gyvfay9gb) {
  d: path("m4 12 4 4");
}

:global(.kkozh6bab) {
  d: path("M11 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

:global(.o0-3vqblf) {
  d: path("M2 8h8");
}

:global(.rns28-8pl) {
  d: path("M8 12.5V16H4.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
