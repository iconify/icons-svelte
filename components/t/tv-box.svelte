<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="znoquvgxk"/><path class="f61izqzht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tv-box" {...props}></Icon>
<style>
:global(.f61izqzht) {
  d: path("M11 11.25v2.5l2.25-1.25Zm-2.75 5.5v2m7.5-2v2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.znoquvgxk) {
  width: 12.5px;
  height: 8.5px;
  x: 5.75px;
  y: 8.25px;
  rx: 2px;
}

</style>
