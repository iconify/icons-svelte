<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_qx0wefi"/><path class="znludhb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ruck" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_qx0wefi) {
  d: path("M2.5 16v-1.5a3 3 0 0 1 6 0a3.5 3.5 0 0 1 7 0a3 3 0 0 1 6 0V16m-18-9.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.25-2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6.75 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2.5 20h19");
}

:global(.znludhb4z) {
  d: path("M8.75 18.5q3.25-3 6.5 0q-3.25 3-6.5 0");
}

</style>
