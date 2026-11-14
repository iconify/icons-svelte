<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux5rrx1ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trend-percent-up" {...props}></Icon>
<style>
:global(.ux5rrx1ev) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 17.5l7-11m-7.25 1a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m9.75 4V4m-3.5 3.5L17 4l3.5 3.5");
}

</style>
