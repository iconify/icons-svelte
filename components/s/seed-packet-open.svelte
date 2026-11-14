<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpw3t180m"/><path class="z7510wrij"/><path class="xhi6qgbno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:seed-packet-open" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xhi6qgbno) {
  fill: currentColor;
  d: path("M17 8.5a1 1.5 0 1 0 2 0a1 1.5 0 1 0-2 0m2 4.5a1 1.5 0 1 0 2 0a1 1.5 0 1 0-2 0m-2 5a1 1.5 0 1 0 2 0a1 1.5 0 1 0-2 0");
}

:global(.z7510wrij) {
  d: path("M8.75 18v-6.5m0 2Q6 13.5 6 11q2.75 0 2.75 2.5m0 0q2.75 0 2.75-2.5q-2.75 0-2.75 2.5");
}

:global(.zpw3t180m) {
  d: path("M3 19.75V6.725a1.75 1.75 0 0 1 .513-1.238L4 5a1.414 1.414 0 0 1 2 0a1.414 1.414 0 0 0 2 0a1.414 1.414 0 0 1 2 0a1.414 1.414 0 0 0 2 0l.25-.25a1.06 1.06 0 0 1 1.5 0l.237.237a1.75 1.75 0 0 1 .513 1.238V19.75a1.75 1.75 0 0 1-1.75 1.75h-8A1.75 1.75 0 0 1 3 19.75");
}

</style>
