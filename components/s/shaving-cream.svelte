<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ot4y_jb9m"/><rect class="gvpatcbjw"/><path class="kvu524b1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shaving-cream" {...props}></Icon>
<style>
:global(.gvpatcbjw) {
  width: 10px;
  height: 8.75px;
  x: 7px;
  y: 12.5px;
  rx: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kvu524b1m) {
  d: path("M7 15.5h10");
}

:global(.ot4y_jb9m) {
  d: path("M7.25 9.5A2.25 2.25 0 0 1 8 5.25a3 3 0 0 1 5.25-.5a3 3 0 0 1 3.5 4.75Z");
}

</style>
