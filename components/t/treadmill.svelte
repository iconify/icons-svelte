<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z_2nl4byy"/><path class="usvnlvbpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:treadmill" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.usvnlvbpc) {
  d: path("M6 18.5h10.5m1-2.25l-2.75-11.5h4.5");
}

:global(.z_2nl4byy) {
  width: 17px;
  height: 4.5px;
  x: 2.75px;
  y: 16.25px;
  rx: 2.25px;
}

</style>
