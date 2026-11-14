<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfslvsbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rowing" {...props}></Icon>
<style>
:global(.rfslvsbsi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5h18c-3.5 4-14.5 4-18 0m13-9l-7 14M2.5 20q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
