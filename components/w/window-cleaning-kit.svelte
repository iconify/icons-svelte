<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifssjtppm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:window-cleaning-kit" {...props}></Icon>
<style>
:global(.ifssjtppm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10h16l-1.5 11h-13Zm.5 3.5h15M8 3h8m-4 0v7");
}

</style>
