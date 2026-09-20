<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dwzg60n6e"/><path class="cu6e5abrj"/><path class="yelo88bjk"/><path class="z9ittvbis"/><path class="cx4rf3b3b"/><path class="mcqgo4bpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:twilight-duotone-bold" {...props}></Icon>
<style>
:global(.cu6e5abrj) {
  fill: currentColor;
  d: path("M18 6.5 20.5 9 18 11.5 15.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cx4rf3b3b) {
  d: path("M6 4.5 8.5 7 6 9.5 3.5 7Z");
}

:global(.dwzg60n6e) {
  fill: currentColor;
  d: path("M6 4.5 8.5 7 6 9.5 3.5 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mcqgo4bpg) {
  d: path("M18 6.5 20.5 9 18 11.5 15.5 9Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yelo88bjk) {
  d: path("M5 18a7 7 0 0 1 14 0");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
