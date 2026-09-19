<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ouxn446sb"/><circle class="il3stz1dw"/><path class="wacvjb61m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vk-play" {...props}></Icon>
<style>
:global(.il3stz1dw) {
  cx: 30.929px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.ouxn446sb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 14.75h37m0 14.5s-6.27 4-18.5 4s-18.5-4-18.5-4");
}

:global(.wacvjb61m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.253 20.818l-6.355 6.356m0-6.348l6.348 6.348");
}

</style>
