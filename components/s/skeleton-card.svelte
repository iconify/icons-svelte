<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yd-ecgb4e"/><path class="m13c-rb1n"/><path class="u0cfjfaql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skeleton-card" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m13c-rb1n) {
  fill: currentColor;
  d: path("M7.75 6.5h.5A1.75 1.75 0 0 1 10 8.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 6 8.75v-.5A1.75 1.75 0 0 1 7.75 6.5");
}

:global(.u0cfjfaql) {
  d: path("M6 13.5h12m-12 4h7");
}

:global(.yd-ecgb4e) {
  d: path("M6.5 3.5h11A3.5 3.5 0 0 1 21 7v10a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17V7a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
