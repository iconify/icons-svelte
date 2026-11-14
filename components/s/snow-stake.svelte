<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjh43zbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:snow-stake" {...props}></Icon>
<style>
:global(.rjh43zbqp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 20.5V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v16.5m-9.5 0h18M12.5 7H16m-3.5 4H15m-2.5 4H16");
}

</style>
