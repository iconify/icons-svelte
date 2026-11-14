<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrs8adk8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sail-mainsail" {...props}></Icon>
<style>
:global(.xrs8adk8g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5c5 4 9 9 11.5 14.5M6 2.5v19M6 17h12.5");
}

</style>
