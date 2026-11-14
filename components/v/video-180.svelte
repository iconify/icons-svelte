<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6lzdw25c"/><path class="r3v5o_i3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:video-180" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6lzdw25c) {
  d: path("M3 4.5q9 4.5 18 0v15q-9-4.5-18 0Z");
}

:global(.r3v5o_i3l) {
  d: path("m12.171 10.585l.329.165a1.398 1.398 0 0 1 0 2.5l-.329.165A1.5 1.5 0 0 1 10 12.073v-.146a1.5 1.5 0 0 1 2.171-1.342");
}

</style>
