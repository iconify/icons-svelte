<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nh6gitbrz"/><path class="dvzhdg8hu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:seismograph" {...props}></Icon>
<style>
:global(.dvzhdg8hu) {
  d: path("M2.75 12h3L8 8.5l3 7l3-7l2.25 3.5h4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nh6gitbrz) {
  width: 16.5px;
  height: 14.5px;
  x: 3.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>
