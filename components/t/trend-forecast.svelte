<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq7htqnnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trend-forecast" {...props}></Icon>
<style>
:global(.tq7htqnnj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 18l4.5-5.5L11 15m2-2l1.5-1.5m2-2L18 8m2.25-2.25h.01");
}

</style>
