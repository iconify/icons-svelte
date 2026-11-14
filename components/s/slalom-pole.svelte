<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmoav976t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:slalom-pole" {...props}></Icon>
<style>
:global(.vmoav976t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5v19m0-18H19V12H8.5M5 21.5h7");
}

</style>
