<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e62fxubid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:superbike" {...props}></Icon>
<style>
:global(.e62fxubid) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0M3 9.5h6l2.5 2.5H14l2-6h2.5l2 3.5M18 16l-2.5-8.5M6 16l5.5-4");
}

</style>
