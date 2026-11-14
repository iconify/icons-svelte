<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="riaurslab"/><path class="jtegwwo-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wheelchair" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jtegwwo-n) {
  d: path("M14.505 12.345a5.5 5.5 0 1 1-9.01 0");
}

:global(.riaurslab) {
  d: path("M8 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10 8v4.5h5.5l2.5 7");
}

</style>
