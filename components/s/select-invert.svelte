<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2f5ecbho"/><path class="ssry9ybuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:select-invert" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o2f5ecbho) {
  d: path("M3.5 7V5.5a2 2 0 0 1 2-2H7m10 0h1.5a2 2 0 0 1 2 2V7m0 10v1.5a2 2 0 0 1-2 2H17m-10 0H5.5a2 2 0 0 1-2-2V17m7-13.5h3m-3 17h3m-10-10v3m17-3v3m-10.375-6h3.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-3.75A2.625 2.625 0 0 1 7.5 13.875v-3.75A2.625 2.625 0 0 1 10.125 7.5");
}

:global(.ssry9ybuz) {
  d: path("M16.5 7.5V15a1.5 1.5 0 0 1-1.5 1.5H7.5Z");
}

</style>
