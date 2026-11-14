<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym6m36xad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:waves-weather" {...props}></Icon>
<style>
:global(.ym6m36xad) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0M3 12q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0M3 17.5q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
