<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eze3ujb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sail-full" {...props}></Icon>
<style>
:global(.eze3ujb-w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5V17M9 3q11.5 5 8 11q-4-1-8 0m-5.5 3h17l-2 3.5h-13Z");
}

</style>
