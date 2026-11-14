<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nmiee-bkz"/><path class="e2-q6xbpt"/><path class="kwmzvp45r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:water-tanker" {...props}></Icon>
<style>
:global(.e2-q6xbpt) {
  d: path("M2.5 16.5h19V12l-3-3.5h-4v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kwmzvp45r) {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.nmiee-bkz) {
  d: path("M6.5 5.5h4a4 4 0 0 1 4 4a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4a4 4 0 0 1 4-4");
}

</style>
