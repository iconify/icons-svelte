<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-dqntbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stemless-wine-glass" {...props}></Icon>
<style>
:global(.e-dqntbrz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5V12c0 5 2.5 8.5 6.5 8.5s6.5-3.5 6.5-8.5V3.5Zm0 6.5h13");
}

</style>
