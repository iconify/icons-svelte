<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gc4hu6bwu"/><path class="y0uafsbqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:storm-cell" {...props}></Icon>
<style>
:global(.gc4hu6bwu) {
  d: path("M20.25 9.75A8.5 8.5 0 1 1 18 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0uafsbqr) {
  d: path("M15 6h3V3M8.5 15h7a2 2 0 0 0 .25-4A3.5 3.5 0 0 0 9 10.75A2.25 2.25 0 0 0 8.5 15");
}

</style>
