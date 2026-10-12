<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="c4diszbug"/><path class="lycgwgkxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stool" {...props}></Icon>
<style>
:global(.c4diszbug) {
  width: 11.5px;
  height: 3.5px;
  x: 6.25px;
  y: 3.75px;
  rx: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lycgwgkxh) {
  d: path("m8.25 7.25l-2 14m9.5-14l2 14M7 16h10");
}

</style>
