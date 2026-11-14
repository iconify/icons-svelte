<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgbtnrx_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:time-zone-difference" {...props}></Icon>
<style>
:global(.xgbtnrx_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m11 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m-6.5 0V9.5m0 2.5L8 13m9.5-1V9.5m0 2.5l1.5 1");
}

</style>
