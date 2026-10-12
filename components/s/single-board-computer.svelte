<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ofoxgrq4c"/><path class="v8g1hmbbw"/><rect class="cg1u9nj-c"/><path class="p5xe5qgzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:single-board-computer" {...props}></Icon>
<style>
:global(.cg1u9nj-c) {
  width: 5.5px;
  height: 5.5px;
  x: 6.25px;
  y: 11px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.ofoxgrq4c) {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.p5xe5qgzb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 12.25h2.5m-2.5 3h2.5");
}

:global(.v8g1hmbbw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.5h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
