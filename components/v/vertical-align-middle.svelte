<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wbbb3na8m"/><rect class="e9rnpc6cn"/><path class="ijs0p36kx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:vertical-align-middle" {...props}></Icon>
<style>
:global(.e9rnpc6cn) {
  width: 5px;
  height: 9px;
  x: 13.75px;
  y: 7.5px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ijs0p36kx) {
  d: path("M2.75 12h18.5");
}

:global(.wbbb3na8m) {
  width: 5px;
  height: 15.5px;
  x: 5.25px;
  y: 4.25px;
  rx: 1.5px;
}

</style>
