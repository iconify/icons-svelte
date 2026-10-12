<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wy-87fpug"/><circle class="krrzio5fu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:top-p-slider" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.krrzio5fu) {
  cx: 18px;
  cy: 9px;
  r: 1.75px;
}

:global(.wy-87fpug) {
  d: path("M4 5.75v15.5m4-11.5v11.5m4-7v7m6-18.5v4.5m0 3.5v10.5");
}

</style>
