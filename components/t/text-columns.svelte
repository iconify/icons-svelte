<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1wcrb42r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:text-columns" {...props}></Icon>
<style>
:global(.k1wcrb42r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h7m-7 5h7m-7 5h7m-7 5H8m5.5-15h7m-7 5h7m-7 5h7m-7 5H18");
}

</style>
