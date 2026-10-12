<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p32cdrbxf"/><rect class="t8-l2ubqr"/><path class="e6_z-_t-t"/><rect class="o_a7uohsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:space-elevator" {...props}></Icon>
<style>
:global(.e6_z-_t-t) {
  d: path("M12 5.25v5m0 3v5.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o_a7uohsk) {
  width: 3px;
  height: 3px;
  x: 10.5px;
  y: 10.25px;
  rx: 0.75px;
}

:global(.p32cdrbxf) {
  d: path("M3.5 21.25a8.5 2.75 0 0 1 17 0Z");
}

:global(.t8-l2ubqr) {
  width: 5px;
  height: 2.5px;
  x: 9.5px;
  y: 2.75px;
  rx: 1px;
}

</style>
