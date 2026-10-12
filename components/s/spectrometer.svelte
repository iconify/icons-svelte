<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sm63zjb8n"/><path class="pzntaqbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spectrometer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pzntaqbfy) {
  d: path("m9.88 9.5l2.75 4.75h-5.5ZM2.75 12H5.5m2.25 5v4.25M12 17v4.25M14.25 12l7-4.5m-7 4.5h7m-7 0l7 4.5");
}

:global(.sm63zjb8n) {
  width: 8.75px;
  height: 10px;
  x: 5.5px;
  y: 7px;
  rx: 1.5px;
}

</style>
