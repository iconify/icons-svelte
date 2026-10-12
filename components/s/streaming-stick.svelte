<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="l7oftfa0v"/><path class="ngw2utd1a"/><rect class="hfzgowbvg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:streaming-stick" {...props}></Icon>
<style>
:global(.hfzgowbvg) {
  width: 5.5px;
  height: 4px;
  x: 15.75px;
  y: 10px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l7oftfa0v) {
  width: 13px;
  height: 7px;
  x: 2.75px;
  y: 8.5px;
  rx: 2px;
}

:global(.ngw2utd1a) {
  d: path("M7.75 10.25v3.5l3-1.75Z");
}

</style>
