<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="impblll8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:zz-plant" {...props}></Icon>
<style>
:global(.impblll8r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16h10l-1 5.5H8Zm5 0V2.5M12 14c-2 0-5-.5-6-3c2.5-.5 5 .5 6 3m0-4.25c2 0 5-.5 6-3c-2.5-.5-5 .5-6 3m0-4.25c-2 0-4.5-.5-5.5-3C9 2 11 3 12 5.5");
}

</style>
