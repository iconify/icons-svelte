<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-mcaibji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:visor-headset" {...props}></Icon>
<style>
:global(.e-mcaibji) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 8.5c3.25-2 10.25-2 13.5 0V14c0 1.5-.75 2.5-2.25 2.5H15c-1 0-1.5-2.75-3-2.75s-2 2.75-3 2.75H7.5c-1.5 0-2.25-1-2.25-2.5Zm0 1.25C3.5 9.75 2.5 10.5 2.5 12v2.5m16.25-4.75c1.75 0 2.75.75 2.75 2.25v2.5");
}

</style>
