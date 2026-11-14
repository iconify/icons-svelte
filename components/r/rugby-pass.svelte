<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epn3m-byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rugby-pass" {...props}></Icon>
<style>
:global(.epn3m-byl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5a10 10 0 0 1 16 0a10 10 0 0 1-16 0m-.5 10H20m-3-3l3 3l-3 3m-8.5-13h7");
}

</style>
