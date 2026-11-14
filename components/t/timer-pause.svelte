<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6m3rnetj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:timer-pause" {...props}></Icon>
<style>
:global(.a6m3rnetj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0M9.5 2.5h5M10.25 10v6m3.5-6v6");
}

</style>
