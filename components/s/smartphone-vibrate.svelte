<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itoa7mbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smartphone-vibrate" {...props}></Icon>
<style>
:global(.itoa7mbqg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.5h2A3.5 3.5 0 0 1 16.5 7v10a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 7.5 17V7A3.5 3.5 0 0 1 11 3.5M4 9v6m16-6v6");
}

</style>
