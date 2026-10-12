<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qwslxfbsh"/><path class="yfn6m1bzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tweezers" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qwslxfbsh) {
  width: 5.5px;
  height: 3.25px;
  x: 9.25px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.yfn6m1bzp) {
  d: path("M10 6L7 20.5l1.5.75M14 6l3 14.5l-1.5.75");
}

</style>
