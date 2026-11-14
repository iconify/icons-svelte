<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xo87uob7k"/><path class="c4raxacly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:signal-head-two" {...props}></Icon>
<style>
:global(.c4raxacly) {
  d: path("M10.5 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xo87uob7k) {
  d: path("M11.875 4.5h.25A4.375 4.375 0 0 1 16.5 8.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-.25A4.375 4.375 0 0 1 7.5 15.125v-6.25A4.375 4.375 0 0 1 11.875 4.5");
}

</style>
