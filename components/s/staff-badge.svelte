<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_2fd7btu"/><path class="tha15zbvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:staff-badge" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tha15zbvk) {
  d: path("M10 11.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8.5 19c0-1.75 1.5-2.5 3.5-2.5s3.5.75 3.5 2.5");
}

:global(.v_2fd7btu) {
  d: path("M9 7.5h6a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 18v-7A3.5 3.5 0 0 1 9 7.5m0 0L12 3m3 4.5L12 3");
}

</style>
