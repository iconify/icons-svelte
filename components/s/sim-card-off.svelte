<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l672kbbzs"/><path class="lo850iize"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sim-card-off" {...props}></Icon>
<style>
:global(.l672kbbzs) {
  d: path("M6.4 2.5h8.1L19 7v8.036M17.564 21.5H5V8.964");
}

:global(.lo850iize) {
  d: path("M13.9 10H16v2.1m-1.4 6.4H8v-6.6m0 2.35h2.3M3.5 3.5l17 17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
