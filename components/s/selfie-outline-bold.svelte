<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d269etb2f"/><path class="iu1vklb-k"/><path class="rrvudvrpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:selfie-outline-bold" {...props}></Icon>
<style>
:global(.d269etb2f) {
  d: path("M6 3v14h10V3Z");
}

:global(.iu1vklb-k) {
  d: path("M9 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rrvudvrpy) {
  d: path("m16 15 4 4v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
