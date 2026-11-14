<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a88uu03mv"/><path class="lyqa_3bpe"/><path class="vm1z6pbjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sell-through-rate" {...props}></Icon>
<style>
:global(.a88uu03mv) {
  d: path("M12 2.5A9.5 9.5 0 1 1 2.5 12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lyqa_3bpe) {
  d: path("m12.699 6.868l3.25 1.71a1.5 1.5 0 0 1 .801 1.328v4.188a1.5 1.5 0 0 1-.801 1.328l-3.25 1.71a1.5 1.5 0 0 1-1.398 0l-3.25-1.71a1.5 1.5 0 0 1-.801-1.328V9.906a1.5 1.5 0 0 1 .801-1.328l3.25-1.71a1.5 1.5 0 0 1 1.398 0");
}

:global(.vm1z6pbjb) {
  d: path("M7.25 9L12 11.5L16.75 9M12 11.5v6");
}

</style>
