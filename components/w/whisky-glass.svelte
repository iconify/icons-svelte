<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rownf_u8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:whisky-glass" {...props}></Icon>
<style>
:global(.rownf_u8k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 4l1.75 14Q6 20 8 20h8q2 0 2.25-2L20 4M4.75 10h14.5M5.5 16.5h13");
}

</style>
