<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wkr6xpbog"/><path class="is8nqnbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:swimming-laps" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.is8nqnbzt) {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

:global(.wkr6xpbog) {
  d: path("M3 5.5q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0M3 11q2.25-2.5 4.5 0t4.5 0t4.5 0q.462.513.924.816m.874.383Q19.649 12.501 21 11m-.25 7.5A2.75 2.75 0 1 1 18 15.75");
}

</style>
