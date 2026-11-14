<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="invur-bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:underfloor-heating-on" {...props}></Icon>
<style>
:global(.invur-bwb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5h18M7 17c-1.5-2.25 1.5-4.75 0-7s1.5-4.75 0-6.5M12 17c-1.5-2.25 1.5-4.75 0-7s1.5-4.75 0-6.5M17 17c-1.5-2.25 1.5-4.75 0-7s1.5-4.75 0-6.5");
}

</style>
