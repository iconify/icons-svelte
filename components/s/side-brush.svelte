<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gj3etsb_q"/><path class="yvdcteb7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:side-brush" {...props}></Icon>
<style>
:global(.gj3etsb_q) {
  d: path("M11.25 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yvdcteb7g) {
  d: path("M13.75 8.5q0-4.5 6.75-5.5M16 12.25q3.75 2.25 1.25 8.5m-5.75-8.5q-3.75 2.25-8-3");
}

</style>
