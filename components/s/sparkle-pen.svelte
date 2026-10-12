<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0v_ydbxx"/><path class="u-h2gd6ms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sparkle-pen" {...props}></Icon>
<style>
:global(.g0v_ydbxx) {
  d: path("M7.75 3h4.5q1 0 1 1v2.5q0 1 .48 1.88l1.79 3.24q.48.88-.09 1.7l-4.86 7.11q-.57.82-1.14 0l-4.86-7.11q-.57-.82-.09-1.7l1.79-3.24q.48-.88.48-1.88V4q0-1 1-1M10 20.5v-6.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u-h2gd6ms) {
  d: path("M10 10.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5m8.25-7.5q.36 2.64 3 3q-2.64.36-3 3q-.36-2.64-3-3q2.64-.36 3-3");
}

</style>
