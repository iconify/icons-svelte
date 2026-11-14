<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="au8lblbdt"/><path class="qaoj3_bnd"/><path class="d7my5z47k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermometer-half" {...props}></Icon>
<style>
:global(.au8lblbdt) {
  d: path("M7.5 12.5v-7a3 3 0 0 1 6 0v7a5 5 0 1 1-6 0");
}

:global(.d7my5z47k) {
  d: path("M10.5 10v6.5M16.25 6h3m-3 4h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qaoj3_bnd) {
  fill: currentColor;
  d: path("M8.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
