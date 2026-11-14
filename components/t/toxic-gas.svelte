<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zft21zohj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:toxic-gas" {...props}></Icon>
<style>
:global(.zft21zohj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12.5a3.25 3.25 0 0 1 0-6.5a6 6 0 0 1 10-.5a3.75 3.75 0 0 1 1 7Zm.5 3q-1.5 1.5 0 3t0 3m5-6q-1.5 1.5 0 3t0 3m5-6q-1.5 1.5 0 3t0 3");
}

</style>
