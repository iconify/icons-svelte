<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a74hefbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:signal-down" {...props}></Icon>
<style>
:global(.a74hefbdn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5V17m3.25 3.5V13m3.25 7.5V9m3.25 11.5v-.4m0-3.2V4.5m5.25 10v7m-3-3l3 3l3-3");
}

</style>
