<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecl-bzb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:traffic-clear" {...props}></Icon>
<style>
:global(.ecl-bzb2i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21.5l5-19m7.5 0l3 11.5M11.75 3v3m0 3.5V13m0 3.5v4m3-2.5l2 2L21 15.75");
}

</style>
