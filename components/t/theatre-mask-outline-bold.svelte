<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h4ns5qbtt"/><path class="c4o3x9bhp"/><path class="a97qfmbix"/><path class="se9hxcxbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:theatre-mask-outline-bold" {...props}></Icon>
<style>
:global(.a97qfmbix) {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.c4o3x9bhp) {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h4ns5qbtt) {
  d: path("M5 5h14v8a7 7 0 0 1 -14 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.se9hxcxbl) {
  d: path("M16 13a4 4 0 0 1 -8 0");
}

</style>
