<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nsc5_ybxi"/><path class="kq6yz8b2a"/><circle class="lzyv8l4fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ventra" {...props}></Icon>
<style>
:global(.kq6yz8b2a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.585 4.5L24 24.486L32.415 4.5");
}

:global(.lzyv8l4fc) {
  cx: 24px;
  cy: 40.002px;
  r: 3.498px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nsc5_ybxi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.585 13.318L24 33.305l8.415-19.987");
}

</style>
