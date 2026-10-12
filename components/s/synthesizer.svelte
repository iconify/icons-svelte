<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="l9mf0ibos"/><path class="xdp0zybrc"/><path class="kp26debrw"/><path class="dsy8v2brp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:synthesizer" {...props}></Icon>
<style>
:global(.dsy8v2brp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 8.25h4.5");
}

:global(.kp26debrw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 8.25h.01m3.24 0h.01");
}

:global(.l9mf0ibos) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.xdp0zybrc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.75h18.5m-13.85 0v7.5m4.6-7.5v7.5m4.6-7.5v7.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
