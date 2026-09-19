<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-73.087 24 24)" class="xtte9sfcj"/><path class="akavgoril"/><rect class="f8iomibaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:uno-alt" {...props}></Icon>
<style>
:global(.akavgoril) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.198 37.381l7.604-26.762M15.659 24h16.699");
}

:global(.f8iomibaa) {
  width: 24px;
  height: 39px;
  x: 12px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.xtte9sfcj) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.915px;
  ry: 8.293px;
}

</style>
