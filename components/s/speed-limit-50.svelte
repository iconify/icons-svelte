<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="rkwx1guqi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:speed-limit-50" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.rkwx1guqi) {
  d: path("M10.75 8h-3.5v3.25H8.5a2.375 2.375 0 0 1 0 4.75H6.75m8.875-8zA1.875 1.875 0 0 1 17.5 9.875v4.25A1.875 1.875 0 0 1 15.625 16a1.875 1.875 0 0 1-1.875-1.875v-4.25A1.875 1.875 0 0 1 15.625 8");
}

</style>
