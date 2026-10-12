<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="csiuwxz_l"/><circle class="dtaoxebzb"/><path class="q492c2byv"/><rect class="ca7bvvass"/><path class="ap3qcob6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:secure-connection" {...props}></Icon>
<style>
:global(.ap3qcob6l) {
  d: path("M10.5 10.5V9a1.5 1.5 0 0 1 3 0v1.5");
}

:global(.ca7bvvass) {
  width: 6px;
  height: 5px;
  x: 9px;
  y: 10.5px;
  rx: 1.25px;
}

:global(.csiuwxz_l) {
  cx: 4.75px;
  cy: 13px;
  r: 2px;
}

:global(.dtaoxebzb) {
  cx: 19.25px;
  cy: 13px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q492c2byv) {
  d: path("M6.75 13H9m6 0h2.25");
}

</style>
