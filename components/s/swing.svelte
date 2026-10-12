<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ptleyrb5p"/><rect class="iilc8fbwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:swing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iilc8fbwv) {
  width: 7px;
  height: 2.25px;
  x: 8.5px;
  y: 14.25px;
  rx: 1.125px;
}

:global(.ptleyrb5p) {
  d: path("M3.25 21.25L6.5 3.75h11l3.25 17.5M10 3.75v10.5m4-10.5v10.5");
}

</style>
