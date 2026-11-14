<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="chmcbdc0x"/><path class="sthqgdbph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trend-down" {...props}></Icon>
<style>
:global(.chmcbdc0x) {
  d: path("m3 6l5 5.5l4-3l8.5 8.5");
}

:global(.sthqgdbph) {
  d: path("M15.5 17h5v-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
