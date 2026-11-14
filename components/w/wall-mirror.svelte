<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn4cfyfjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wall-mirror" {...props}></Icon>
<style>
:global(.xn4cfyfjl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12a7 9.5 0 1 0 14 0a7 9.5 0 1 0-14 0m3.5-1l4-4");
}

</style>
