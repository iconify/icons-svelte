<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ufqune_dy"/><path class="tzwavhcpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-polo-goal" {...props}></Icon>
<style>
:global(.tzwavhcpu) {
  d: path("M3.5 4.5L7 8.25h10l3.5-3.75M7 8.25V16m10-7.75V16M2.5 19.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

:global(.ufqune_dy) {
  d: path("M3.5 16V4.5h17V16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
