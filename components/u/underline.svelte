<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7_k89_3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:underline" {...props}></Icon>
<style>
:global(.q7_k89_3v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4v6.5a5 5 0 0 0 10 0V4M5.5 20h13");
}

</style>
