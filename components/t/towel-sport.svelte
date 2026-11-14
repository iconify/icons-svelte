<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daxjslm9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:towel-sport" {...props}></Icon>
<style>
:global(.daxjslm9o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19M6 3v15h12V3M6 14.5h12M8.5 18v3m3.5-3v3m3.5-3v3");
}

</style>
