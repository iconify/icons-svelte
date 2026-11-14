<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1iewlb9a"/><path class="toil9ablh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spatial-widget" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.toil9ablh) {
  d: path("M21.5 6.5v12a3 3 0 0 1-3 3h-12m0-11a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.y1iewlb9a) {
  d: path("M7.75 2.5h5.5a5.25 5.25 0 0 1 5.25 5.25v5.5a5.25 5.25 0 0 1-5.25 5.25h-5.5a5.25 5.25 0 0 1-5.25-5.25v-5.5A5.25 5.25 0 0 1 7.75 2.5");
}

</style>
