<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v1m54nlcr"/><path class="wdth6dbso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tidal-bore" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v1m54nlcr) {
  d: path("M2.5 19c6 0 6.5-14 13-14c3.75 0 5.5 3.25 3.75 5.5C18 12 15.5 11.25 16 9.25");
}

:global(.wdth6dbso) {
  d: path("M2.5 19H16l2.5-3h3");
}

</style>
