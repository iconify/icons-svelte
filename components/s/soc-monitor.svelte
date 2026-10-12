<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="c0d86hb-h"/><rect class="bvn8pdmli"/><path class="z7dp1rb3v"/><circle class="omcoudbor"/><path class="c27t4nc2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:soc-monitor" {...props}></Icon>
<style>
:global(.bvn8pdmli) {
  width: 7.75px;
  height: 7px;
  x: 13.5px;
  y: 3px;
  rx: 1.5px;
}

:global(.c0d86hb-h) {
  width: 7.75px;
  height: 7px;
  x: 2.75px;
  y: 3px;
  rx: 1.5px;
}

:global(.c27t4nc2l) {
  d: path("M7.5 21.25a4.5 4.5 0 0 1 9 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.omcoudbor) {
  cx: 12px;
  cy: 14.75px;
  r: 2.25px;
}

:global(.z7dp1rb3v) {
  d: path("m4.75 7l1.5-1.5l1.25 1l1.25-1.25M15.5 6.5h3.75");
}

</style>
