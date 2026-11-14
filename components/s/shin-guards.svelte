<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnnmlab-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shin-guards" {...props}></Icon>
<style>
:global(.lnnmlab-g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5q3-2.5 6 0l-.75 10q1.25 2.5.5 5.5h-5.5q-.75-3 .5-5.5Zm10 0q3-2.5 6 0l-.75 10q1.25 2.5.5 5.5h-5.5q-.75-3 .5-5.5Z");
}

</style>
