<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3dy98b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sprout-pair" {...props}></Icon>
<style>
:global(.i3dy98b1u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5V10m0 0c0-4-2.5-6.5-7.5-6.5c0 4 3 6.5 7.5 6.5m0 0c0-4 2.5-6.5 7.5-6.5c0 4-3 6.5-7.5 6.5");
}

</style>
