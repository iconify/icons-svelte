<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><rect class="a7181ubik"/><path class="tip2y0epd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:street-view" {...props}></Icon>
<style>
:global(.a7181ubik) {
  width: 6px;
  height: 9.5px;
  x: 9px;
  y: 9px;
  rx: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tip2y0epd) {
  d: path("M8.25 17.5c-3.25.4-5.5 1.15-5.5 2c0 1 4.15 1.75 9.25 1.75s9.25-.75 9.25-1.75c0-.85-2.25-1.6-5.5-2");
}

:global(.wv5f_1brg) {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
