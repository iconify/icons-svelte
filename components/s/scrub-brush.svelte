<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gimb-jbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scrub-brush" {...props}></Icon>
<style>
:global(.gimb-jbmc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11h7a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 12 16H5a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 5 11m7.5 0l8-8M5 16v3m3.5-3v3m3.5-3v3");
}

</style>
