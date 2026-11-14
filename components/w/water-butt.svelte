<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfrlrrb_j"/><path class="znwst_b2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:water-butt" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xfrlrrb_j) {
  d: path("M5 3h10c1.5 5 1.5 13 0 18H5C3.5 16 3.5 8 5 3M4 8.25h12");
}

:global(.znwst_b2t) {
  d: path("M16 15.5h3.5V18");
}

</style>
