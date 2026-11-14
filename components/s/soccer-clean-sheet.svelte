<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oacnj-lpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:soccer-clean-sheet" {...props}></Icon>
<style>
:global(.oacnj-lpf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19V5h18v7.9M3 19L17 5M3 10l9 9M9 5l9.405 9.405M14.75 18l2 2L21 15.75");
}

</style>
