<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffu5qhxvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smog-city" {...props}></Icon>
<style>
:global(.ffu5qhxvd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19m-18 0v-7h5V9.75h6v2.75h6V21M4 3.5q2-1.25 4 0t4 0t4 0t4 0M4 6.25q2-1.25 4 0t4 0t4 0t4 0");
}

</style>
