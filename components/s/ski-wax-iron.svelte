<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6qepyb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-wax-iron" {...props}></Icon>
<style>
:global(.a6qepyb4j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 14.5l2.5-5c.75-1.5 2-2 3.5-2h11.5v7Zm7.5-7V4h8v3.5M2.5 19h19");
}

</style>
