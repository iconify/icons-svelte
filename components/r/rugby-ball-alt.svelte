<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6dkohb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rugby-ball-alt" {...props}></Icon>
<style>
:global(.v6dkohb8v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a10.25 10.25 0 0 1 19 0a10.25 10.25 0 0 1-19 0M8 12h8m-7-1.5v3m3-3v3m3-3v3");
}

</style>
