<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="m8gr1ldps"/><circle class="e-ysxcb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:segmentation" {...props}></Icon>
<style>
:global(.a_-q_pb0z) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

:global(.e-ysxcb4m) {
  cx: 15.75px;
  cy: 7.5px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m8gr1ldps) {
  d: path("M2.75 14.25c4.5-.25 7-3.5 7.25-11.5m-.25 18.5c.5-4.75 4.5-7.75 11.5-8");
}

</style>
