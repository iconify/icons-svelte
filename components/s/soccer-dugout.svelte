<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0zc2qmqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:soccer-dugout" {...props}></Icon>
<style>
:global(.x0zc2qmqf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20v-8a9.5 8 0 0 1 19 0v8m-15-4.5h11m-9.5 0V20m8-4.5V20");
}

</style>
