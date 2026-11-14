<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtvydcbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sea-spray" {...props}></Icon>
<style>
:global(.wtvydcbtr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c5 0 5.5-11.5 12-11.5c4.5 0 7 4 5 7c-1.5 2-4.5 1.5-4.25-1.25m-8.5-8.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.5-2.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M18 4.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
