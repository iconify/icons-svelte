<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v2-c9yb3h"/><path class="wrzhaubou"/><path class="q1bxsco5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stadium" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q1bxsco5j) {
  d: path("M2.5 14a9.5 3.5 0 0 0 19 0");
}

:global(.v2-c9yb3h) {
  d: path("M2.5 11a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0");
}

:global(.wrzhaubou) {
  d: path("M2.5 11v6a9.5 3.5 0 0 0 19 0v-6M7 8V3l3 1.25L7 5.5M17 8V3l3 1.25l-3 1.25");
}

</style>
