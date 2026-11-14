<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvdx9j9uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:severance-pay" {...props}></Icon>
<style>
:global(.cvdx9j9uz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12h14.5A1.75 1.75 0 0 1 21 13.75v6a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19.75v-6A1.75 1.75 0 0 1 4.75 12M13 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3-1v2M8 12V6.5M8 9c0-2-1.5-3.5-3.5-3.5C4.5 7.5 6 9 8 9m0-1.5c0-2.25 1.5-3.75 3.5-3.75c0 2-1.5 3.75-3.5 3.75M3 12L2 9.5M21 12l1-2.5");
}

</style>
