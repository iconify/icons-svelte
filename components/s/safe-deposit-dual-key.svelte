<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib1tg1grv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:safe-deposit-dual-key" {...props}></Icon>
<style>
:global(.ib1tg1grv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0m5.25 2.25L19.5 19.5M15 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0m.75 2.25L4.5 19.5m12.75-2.25L15.5 19m-.5-4l-1.5 1.5m-6.75.75L8.5 19m.5-4l1.5 1.5");
}

</style>
