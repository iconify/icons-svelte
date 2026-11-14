<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="posqoj8pk"/><path class="yz_4d5byv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:water-bowl" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.posqoj8pk) {
  d: path("M3 6.5h18a9 9 0 0 1-18 0m6 12h6");
}

:global(.yz_4d5byv) {
  d: path("M7.5 10.5q1.5-1.25 3 0t3 0t3 0");
}

</style>
