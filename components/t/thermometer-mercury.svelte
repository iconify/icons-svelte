<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhz8vybvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermometer-mercury" {...props}></Icon>
<style>
:global(.rhz8vybvr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14V4.5a1.5 1.5 0 0 1 3 0V14a3.5 3.5 0 1 1-3 0M10 8.5v7m4.5-10H17M14.5 9H17m-2.5 3.5H17M14.5 16H17");
}

</style>
