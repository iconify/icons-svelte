<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fp0jerb6p"/><path class="tqfrzx00u"/><path class="af2s8oowp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:video-generate-outline-bold" {...props}></Icon>
<style>
:global(.af2s8oowp) {
  d: path("M10.5 9.5 8 12h2.5L8 14.5");
}

:global(.fp0jerb6p) {
  d: path("M10.5 6H13a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tqfrzx00u) {
  d: path("m19 10 3 -3v10l-3 -3Z");
}

</style>
