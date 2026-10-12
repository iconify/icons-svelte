<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="syxmtqd-u"/><path class="qku6atb4g"/><rect class="lbpz7v40p"/><rect class="s1_z59bmw"/><path class="eh0jr5bay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:waiting-room" {...props}></Icon>
<style>
:global(.eh0jr5bay) {
  d: path("M2.75 18h18.5M5 18v3.25M19 18v3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lbpz7v40p) {
  width: 7px;
  height: 6.5px;
  x: 3.25px;
  y: 11.5px;
  rx: 1.5px;
}

:global(.qku6atb4g) {
  d: path("M17.5 4.5V6l1 1");
}

:global(.s1_z59bmw) {
  width: 7px;
  height: 6.5px;
  x: 13.75px;
  y: 11.5px;
  rx: 1.5px;
}

:global(.syxmtqd-u) {
  cx: 17.5px;
  cy: 6px;
  r: 3.25px;
}

</style>
