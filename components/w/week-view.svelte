<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="luxaszu4f"/><path class="anfakeb6t"/><rect class="i-ogpjbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:week-view" {...props}></Icon>
<style>
:global(.anfakeb6t) {
  d: path("M3.25 8.25h17.5M9 8.25v4.25m0 2v6.25m6-12.5v4.25m0 2v6.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-ogpjbmk) {
  width: 6px;
  height: 4px;
  x: 9px;
  y: 11.5px;
  rx: 1px;
}

:global(.luxaszu4f) {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  rx: 2.5px;
}

</style>
