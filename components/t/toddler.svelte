<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ckdeowbwc"/><rect class="mzopf65bd"/><path class="eoy161bps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toddler" {...props}></Icon>
<style>
:global(.ckdeowbwc) {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
}

:global(.eoy161bps) {
  d: path("M10.5 17v4.25m3-4.25v4.25m-4.75-8L6 10.75m9.25 2.5l2.75-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mzopf65bd) {
  width: 6px;
  height: 5.5px;
  x: 9px;
  y: 11.5px;
  rx: 2.5px;
}

</style>
