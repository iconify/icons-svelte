<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="e1_poib1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:softball" {...props}></Icon>
<style>
:global(.e1_poib1n) {
  d: path("M6 4.75a10.25 10.25 0 0 1 0 14.5m12-14.5a10.25 10.25 0 0 0 0 14.5M7 8h2.5m-1.75 4h2.5M7 16h2.5m5-8H17m-3.25 4h2.5m-1.75 4H17");
}

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

</style>
