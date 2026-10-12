<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lv9esmbjh"/><path class="uekllowgs"/><circle class="cql1pwtbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tower-pc" {...props}></Icon>
<style>
:global(.cql1pwtbp) {
  cx: 12px;
  cy: 16px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lv9esmbjh) {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 2px;
}

:global(.uekllowgs) {
  d: path("M9.25 6.25h5.5m-5.5 3h5.5");
}

</style>
