<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iye_nsb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rupee-sign" {...props}></Icon>
<style>
:global(.iye_nsb2g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4h4c2.5 0 4.25 1.75 4.25 4.25s-1.75 4.5-4.25 4.5h-4l9 7.75M6.5 4H18M6.5 8.25H18");
}

</style>
