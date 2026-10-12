<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="evfw90e9e"/><path class="nx0zbqn7m"/><rect class="lguiyqoyb"/><path class="rmxoesa2q"/><rect class="s20769bun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rubber-stamp" {...props}></Icon>
<style>
:global(.evfw90e9e) {
  width: 8.5px;
  height: 3px;
  x: 7.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lguiyqoyb) {
  width: 10.5px;
  height: 7.5px;
  x: 6.75px;
  y: 8px;
  rx: 1.5px;
}

:global(.nx0zbqn7m) {
  d: path("M7.75 4.25h-4v14m12.5-14h4v14");
}

:global(.rmxoesa2q) {
  d: path("M9.5 11.75h5m-2.5-6V8");
}

:global(.s20769bun) {
  width: 12.5px;
  height: 3.5px;
  x: 5.75px;
  y: 17.75px;
  rx: 1px;
}

</style>
