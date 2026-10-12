<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="l2lx9bb2c"/><rect class="a4uhnib_r"/><rect class="oqn8wgbju"/><rect class="nhxn97bef"/><path class="mnu_r7b3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-gallery" {...props}></Icon>
<style>
:global(.a4uhnib_r) {
  width: 7.75px;
  height: 7.75px;
  x: 13.5px;
  y: 2.75px;
  rx: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l2lx9bb2c) {
  width: 7.75px;
  height: 7.75px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

:global(.mnu_r7b3y) {
  d: path("m5.93 5.25l1.89 1.13q.43.25 0 .5L5.93 8q-.43.25-.43-.25V5.5q0-.5.43-.25");
}

:global(.nhxn97bef) {
  width: 7.75px;
  height: 7.75px;
  x: 13.5px;
  y: 13.5px;
  rx: 2px;
}

:global(.oqn8wgbju) {
  width: 7.75px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 2px;
}

</style>
