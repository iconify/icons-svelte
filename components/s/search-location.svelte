<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="polw-1gzh"/><path class="aurc8q0mo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:search-location" {...props}></Icon>
<style>
:global(.aurc8q0mo) {
  d: path("M10.5 14s-2.75-2.25-2.75-4.25a2.75 2.75 0 0 1 5.5 0c0 2-2.75 4.25-2.75 4.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.polw-1gzh) {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0m12 5l5 5");
}

</style>
