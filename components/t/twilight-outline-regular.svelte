<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yelo88bjk"/><path class="z9ittvbis"/><path class="cx4rf3b3b"/><path class="mcqgo4bpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:twilight-outline-regular" {...props}></Icon>
<style>
:global(.cx4rf3b3b) {
  d: path("M6 4.5 8.5 7 6 9.5 3.5 7Z");
}

:global(.mcqgo4bpg) {
  d: path("M18 6.5 20.5 9 18 11.5 15.5 9Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yelo88bjk) {
  d: path("M5 18a7 7 0 0 1 14 0");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
