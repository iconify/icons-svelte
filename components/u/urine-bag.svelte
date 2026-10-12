<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wxqula1vx"/><path class="cpnn9wn6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:urine-bag" {...props}></Icon>
<style>
:global(.cpnn9wn6m) {
  d: path("M15 10.5h-2.5m2.5 3h-1.5m1.5 3h-2.5m-1-9v-3a1.75 1.75 0 0 0-3.5 0m0 15v1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wxqula1vx) {
  width: 13px;
  height: 12px;
  x: 5px;
  y: 7.5px;
  rx: 2.5px;
}

</style>
