<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dsohl-s8p"/><path class="j0qmvz90d"/><rect class="mn9zz_10d"/><path class="nlyh2zbmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:waxing-strip" {...props}></Icon>
<style>
:global(.dsohl-s8p) {
  width: 12px;
  height: 9px;
  x: 2.75px;
  y: 5.75px;
  rx: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j0qmvz90d) {
  d: path("m5.75 8.5l.75 3.25M8.75 8.5l.75 3.25m2.25-3.25l.75 3.25");
}

:global(.mn9zz_10d) {
  width: 3.5px;
  height: 6px;
  x: 17.75px;
  y: 7.25px;
  rx: 1.25px;
}

:global(.nlyh2zbmv) {
  d: path("M2.75 19.25c3-1.25 6.15-1.25 9.25 0s6.25 1.25 9.25 0");
}

</style>
