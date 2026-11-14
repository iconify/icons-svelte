<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jefgrcc3u"/><path class="bzirq8bkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stop-ahead-sign" {...props}></Icon>
<style>
:global(.bzirq8bkg) {
  d: path("M10.871 8h2.258a1.5 1.5 0 0 1 1.06.439l1.372 1.372a1.5 1.5 0 0 1 .439 1.06v2.258a1.5 1.5 0 0 1-.439 1.06l-1.372 1.372a1.5 1.5 0 0 1-1.06.439h-2.258a1.5 1.5 0 0 1-1.06-.439l-1.372-1.372A1.5 1.5 0 0 1 8 13.129v-2.258a1.5 1.5 0 0 1 .439-1.06l1.372-1.372A1.5 1.5 0 0 1 10.871 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jefgrcc3u) {
  d: path("m14.475 4.725l4.8 4.8a3.5 3.5 0 0 1 0 4.95l-4.8 4.8a3.5 3.5 0 0 1-4.95 0l-4.8-4.8a3.5 3.5 0 0 1 0-4.95l4.8-4.8a3.5 3.5 0 0 1 4.95 0");
}

</style>
