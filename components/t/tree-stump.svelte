<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t2hbpobes"/><path class="hx9y0czch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tree-stump" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hx9y0czch) {
  d: path("M5.75 8.5a6.25 2.5 0 0 0 12.5 0M9.5 14v4.5m8.75-5q2.25-.375 3-2.25");
}

:global(.t2hbpobes) {
  d: path("M5.75 8.5a6.25 2.5 0 0 1 12.5 0v9.25c0 1.25.75 2.5 2.5 3.5H3.25c1.75-1 2.5-2.25 2.5-3.5Z");
}

</style>
