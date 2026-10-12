<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la_3bbc_g"/><path class="excex_8yl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tv-series" {...props}></Icon>
<style>
:global(.excex_8yl) {
  d: path("M7.5 21.25h6M6.75 4.75h12a2.5 2.5 0 0 1 2.5 2.5v8M5.25 13h1.5m3 0h1.5m3 0h1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.la_3bbc_g) {
  width: 15.5px;
  height: 10.5px;
  x: 2.75px;
  y: 7.75px;
  rx: 2.5px;
}

</style>
