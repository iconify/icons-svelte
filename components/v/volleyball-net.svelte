<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtu3-bbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:volleyball-net" {...props}></Icon>
<style>
:global(.vtu3-bbun) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h16a1.5 1.5 0 0 1 1.5 1.5v7A1.5 1.5 0 0 1 20 16H4a1.5 1.5 0 0 1-1.5-1.5v-7A1.5 1.5 0 0 1 4 6m-1.5 5h19M7 6v10m5-10v10m5-10v10M3 16v5.5M21 16v5.5");
}

</style>
