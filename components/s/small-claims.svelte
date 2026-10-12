<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="dk_2fdb8d"/><circle class="em9cvctqt"/><path class="b4gzso3dl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:small-claims" {...props}></Icon>
<style>
:global(.b4gzso3dl) {
  d: path("M12 13.5v3");
}

:global(.dk_2fdb8d) {
  d: path("M8.25 6.5h7.5m-7.5 2.75h5");
}

:global(.em9cvctqt) {
  cx: 12px;
  cy: 15px;
  r: 3.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x00qgzx7x) {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
