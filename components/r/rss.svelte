<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma71c_gpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rss" {...props}></Icon>
<style>
:global(.ma71c_gpu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 11.75a7 7 0 0 1 7 7m-7-13.25A13.25 13.25 0 0 1 19 18.75M5 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
