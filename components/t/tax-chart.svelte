<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqnbty6mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tax-chart" {...props}></Icon>
<style>
:global(.pqnbty6mp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h9.6m-7.6 0V15m4 5.5v-10m4 9.1V4.5m2.25 16.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
