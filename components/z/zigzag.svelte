<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxt2psh3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:zigzag" {...props}></Icon>
<style>
:global(.sxt2psh3f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 10.25l4.5-4.5l4.5 4.5l4.5-4.5l4.5 4.5m-18 8l4.5-4.5l4.5 4.5l4.5-4.5l4.5 4.5");
}

</style>
