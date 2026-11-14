<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a_7ymxgba"/><path class="jkjz5bc5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wing-nut" {...props}></Icon>
<style>
:global(.a_7ymxgba) {
  d: path("M10.25 12h3.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 13.75 18h-3.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 10.25 12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkjz5bc5f) {
  d: path("M8.5 15C5.5 15 3 11 3 6.5c3.5 1 6 3 6.5 5.5m6 3c3 0 5.5-4 5.5-8.5c-3.5 1-6 3-6.5 5.5M12 18v2.5");
}

</style>
