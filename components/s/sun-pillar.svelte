<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm7qs6bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sun-pillar" {...props}></Icon>
<style>
:global(.wm7qs6bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19M7 20a5 5 0 0 1 10 0M10 2.5V12m4-9.5V12");
}

</style>
