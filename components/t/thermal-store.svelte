<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rd2nzflbv"/><path class="nfm6lrb4u"/><path class="y4p_12bzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermal-store" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nfm6lrb4u) {
  d: path("M6 5v14a6 2 0 0 0 12 0V5");
}

:global(.rd2nzflbv) {
  d: path("M6 5a6 2 0 1 0 12 0A6 2 0 1 0 6 5");
}

:global(.y4p_12bzv) {
  d: path("M9 13q1.5-1.5 3 0t3 0m3-3.5h3.5m-19 8H6");
}

</style>
