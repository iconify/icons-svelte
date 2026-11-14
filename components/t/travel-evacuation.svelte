<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odhzxlgtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:travel-evacuation" {...props}></Icon>
<style>
:global(.odhzxlgtq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14a6 4 0 1 0 12 0a6 4 0 1 0-12 0M4 6h16m-8 0v4m4.5 3l5-2m-14 8.5H16");
}

</style>
