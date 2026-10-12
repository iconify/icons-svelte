<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lkve0tb3s"/><path class="zxa3sv3va"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:upscale-ai" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lkve0tb3s) {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 2px;
}

:global(.zxa3sv3va) {
  d: path("M6.75 13.25v8m-4-4h8M10 2.75h8.75a2.5 2.5 0 0 1 2.5 2.5V14m-8.5-2.75l5.5-5.5m-4.5 0h4.5v4.5");
}

</style>
