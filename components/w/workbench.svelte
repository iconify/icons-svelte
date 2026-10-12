<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z9xt8iyeh"/><path class="xv8-tn3dv"/><rect class="gcw17wuuq"/><path class="hsts5rbmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:workbench" {...props}></Icon>
<style>
:global(.gcw17wuuq) {
  width: 7.5px;
  height: 4.5px;
  x: 8.25px;
  y: 9px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsts5rbmz) {
  d: path("M11 11.25h2");
}

:global(.xv8-tn3dv) {
  d: path("M5.25 9v12.25M18.75 9v12.25M5.25 17h13.5");
}

:global(.z9xt8iyeh) {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 5.5px;
  rx: 1.25px;
}

</style>
