<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dkdy6-cum"/><path class="vxae1vbtu"/><rect class="oxnu5ebhk"/><path class="iakgx8buv"/><rect class="dmbr4k02e"/><path class="vlfthvbes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shutters" {...props}></Icon>
<style>
:global(.dkdy6-cum) {
  width: 3.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 1px;
}

:global(.dmbr4k02e) {
  width: 5.5px;
  height: 13.5px;
  x: 9.25px;
  y: 5.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iakgx8buv) {
  d: path("M17.75 7.75h3.5M17.75 12h3.5m-3.5 4.25h3.5");
}

:global(.oxnu5ebhk) {
  width: 3.5px;
  height: 16.5px;
  x: 17.75px;
  y: 3.75px;
  rx: 1px;
}

:global(.vlfthvbes) {
  d: path("M12 5.25v13.5");
}

:global(.vxae1vbtu) {
  d: path("M2.75 7.75h3.5M2.75 12h3.5m-3.5 4.25h3.5");
}

</style>
