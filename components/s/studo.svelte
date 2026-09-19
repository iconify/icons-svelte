<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 24 24)" class="waz0iftqk"/><circle class="dogxzo4ur"/><path class="lxndv_bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:studo" {...props}></Icon>
<style>
:global(.dogxzo4ur) {
  cx: 24px;
  cy: 24px;
  r: 4.346px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lxndv_bxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.927 20.927l-8.451-8.451");
}

:global(.waz0iftqk) {
  width: 32.594px;
  height: 32.594px;
  x: 7.703px;
  y: 7.703px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6px;
}

</style>
