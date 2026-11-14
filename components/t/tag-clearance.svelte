<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyi3fhysh"/><path class="wdo-tu5od"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tag-clearance" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wdo-tu5od) {
  d: path("M6.788 8.288a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3.267 4.949l6.188-.176");
}

:global(.yyi3fhysh) {
  d: path("M6.325 4.575h4.597a1.75 1.75 0 0 1 1.237.513l8.503 8.503a1.75 1.75 0 0 1 0 2.475l-4.596 4.596a1.75 1.75 0 0 1-2.475 0l-8.503-8.503a1.75 1.75 0 0 1-.513-1.237V6.325a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
