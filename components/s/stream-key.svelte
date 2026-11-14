<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7idoylhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stream-key" {...props}></Icon>
<style>
:global(.n7idoylhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0m5.25 2.25l9.25 9.25m-2-2l-1.75 1.75M16 16l-1.75 1.75M3.804 12a6 6 0 0 1 0-6M6 3.804a6 6 0 0 1 6 0");
}

</style>
