<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o2tws2j4q"/><circle class="qhvrk_ymv"/><path class="sqcb-fb9g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:time-slot" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o2tws2j4q) {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 6px;
  rx: 2.5px;
}

:global(.qhvrk_ymv) {
  cx: 8.25px;
  cy: 12px;
  r: 3px;
}

:global(.sqcb-fb9g) {
  d: path("M8.25 10.5V12l1 .75m5-2.5h3.5m-3.5 3.5h2");
}

</style>
