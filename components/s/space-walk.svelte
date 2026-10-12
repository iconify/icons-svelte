<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w09f2snjy"/><rect class="wo1wvr-nr"/><path class="x9u7m09lp"/><circle class="lbbj3sidx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:space-walk" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lbbj3sidx) {
  cx: 4.75px;
  cy: 17.5px;
  r: 2px;
}

:global(.w09f2snjy) {
  cx: 14.5px;
  cy: 5.75px;
  r: 3px;
}

:global(.wo1wvr-nr) {
  width: 7px;
  height: 7.5px;
  x: 11px;
  y: 11.25px;
  rx: 2px;
}

:global(.x9u7m09lp) {
  d: path("m18 13l2.5 2M11 13l-2-1.75m2 5.25c-1.5 0-2.5 1-4.25 1");
}

</style>
