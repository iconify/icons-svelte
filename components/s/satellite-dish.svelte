<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="upg_xtb9x"/><circle class="ha_6x11ur"/><path class="pb24y7jmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:satellite-dish" {...props}></Icon>
<style>
:global(.ha_6x11ur) {
  cx: 14.75px;
  cy: 9.25px;
  r: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pb24y7jmt) {
  d: path("M16.25 5.5A2.75 2.75 0 0 1 19 8.25M16.25 3a5 5 0 0 1 5 5");
}

:global(.upg_xtb9x) {
  d: path("M5.25 8L16 18.75A7.6 7.6 0 0 1 5.25 8m5.38 5.38L14 10");
}

</style>
