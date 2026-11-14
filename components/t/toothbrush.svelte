<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fef-m1big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:toothbrush" {...props}></Icon>
<style>
:global(.fef-m1big) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l9.5-9.5m.75-.75l3.5-3.5a1.06 1.06 0 0 1 1.5 0a1.06 1.06 0 0 1 0 1.5l-3.5 3.5a1.06 1.06 0 0 1-1.5 0a1.06 1.06 0 0 1 0-1.5m.25-.25L12 9m3.5-.5L14 7m3.5-.5L16 5");
}

</style>
