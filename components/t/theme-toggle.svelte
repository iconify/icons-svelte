<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jq91eijwj"/><path class="dsvzlvb9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:theme-toggle" {...props}></Icon>
<style>
:global(.dsvzlvb9u) {
  d: path("M17.25 9a3.25 3.25 0 1 0 1.5 5a2.75 2.75 0 0 1-1.5-5M8.5 12h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jq91eijwj) {
  d: path("M8.5 6h7a6 6 0 0 1 6 6a6 6 0 0 1-6 6h-7a6 6 0 0 1-6-6a6 6 0 0 1 6-6");
}

</style>
