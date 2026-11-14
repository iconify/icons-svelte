<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w13lzbngb"/><path class="q7eexkvah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shortboard" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q7eexkvah) {
  d: path("m14 14l3.5 4.5l-3.75-.5");
}

:global(.w13lzbngb) {
  d: path("M10.5 3.5C14.5 8 15 15 13 20.5H8C6 15 6.5 8 10.5 3.5");
}

</style>
