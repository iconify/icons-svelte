<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hrhyb1bxi"/><circle class="qy61aob5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toggle-on" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrhyb1bxi) {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 6.5px;
  rx: 5.5px;
}

:global(.qy61aob5q) {
  cx: 15.75px;
  cy: 12px;
  r: 3px;
}

</style>
