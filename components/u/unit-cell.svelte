<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn5uwpb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:unit-cell" {...props}></Icon>
<style>
:global(.wn5uwpb8c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5h10m2 2v10m-2 2H7m-2-2V7m4.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m14 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M3 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m14 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
