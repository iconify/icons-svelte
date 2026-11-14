<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyhqs1e1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scroll-to-top" {...props}></Icon>
<style>
:global(.fyhqs1e1y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4h14M6.5 13L12 7.5l5.5 5.5m-11 6l5.5-5.5l5.5 5.5");
}

</style>
