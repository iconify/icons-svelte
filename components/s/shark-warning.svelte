<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b197bdc5d"/><path class="uq89zgw5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shark-warning" {...props}></Icon>
<style>
:global(.b197bdc5d) {
  d: path("m14.291 7.101l5.026 8.993A2.625 2.625 0 0 1 17.026 20H6.974a2.625 2.625 0 0 1-2.291-3.906l5.026-8.993a2.625 2.625 0 0 1 4.582 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uq89zgw5n) {
  d: path("M8 16.5c1.5-2 3-5.5 6.5-7v7Z");
}

</style>
