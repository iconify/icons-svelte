<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e91i0teyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spiral-conveyor" {...props}></Icon>
<style>
:global(.e91i0teyo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7c0-2 14-2 14 0S5 9 5 11s14 2 14 4s-14 2-14 4");
}

</style>
