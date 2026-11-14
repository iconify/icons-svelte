<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc2fk5g0j"/><path class="icy19obja"/><path class="y4goolmub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:temperature-ai" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icy19obja) {
  fill: currentColor;
  d: path("M7 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.tc2fk5g0j) {
  d: path("M6 13.25V5.5a3 3 0 0 1 6 0v7.75a4.75 4.75 0 1 1-6 0");
}

:global(.y4goolmub) {
  d: path("M9 17v-6.5M18 3q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3");
}

</style>
