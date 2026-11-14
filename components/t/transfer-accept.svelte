<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_2didb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:transfer-accept" {...props}></Icon>
<style>
:global(.w_2didb-b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h13m-3.5-3.5L17 6l-3.5 3.5M20 12H7m3.5-3.5L7 12l3.5 3.5m4.25 2.5l2 2L21 15.75");
}

</style>
