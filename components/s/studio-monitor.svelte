<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rwhm97h2q"/><rect class="ioslhmxdl"/><circle class="c56lwnbsh"/><path class="hz4fdebup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:studio-monitor" {...props}></Icon>
<style>
:global(.c56lwnbsh) {
  cx: 12px;
  cy: 13.25px;
  r: 2.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hz4fdebup) {
  d: path("M12 18.5v2.75m-4 0h8");
}

:global(.ioslhmxdl) {
  width: 4.5px;
  height: 2.5px;
  x: 9.75px;
  y: 5.25px;
  rx: 1px;
}

:global(.rwhm97h2q) {
  width: 13.5px;
  height: 15.75px;
  x: 5.25px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
