<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_gmocbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:volleyball-antenna" {...props}></Icon>
<style>
:global(.t_gmocbqs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5V9h19v12.5m-19-6h19M18.25 9V2.5M8.75 9v6.5m5.5-6.5v6.5");
}

</style>
