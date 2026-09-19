<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fg1e8jb0n"/><path class="t-p8-o_xb"/><circle class="wtvflw8rc"/><circle class="sjq238b6p"/><path class="e3uzb33kp"/><circle class="uy5zjtbgn"/><circle class="g2lobhhoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:socratic" {...props}></Icon>
<style>
:global(.e3uzb33kp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.279 15.596h-2.693m-9.99 0h-2.508a2.187 2.187 0 0 0-2.23 2.231m15.03 9.141a1.761 1.761 0 1 1-3.523 0m8.991 0a1.761 1.761 0 1 1-3.522 0m.954 3.554a1.761 1.761 0 1 1-3.523 0");
}

:global(.fg1e8jb0n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.088 22.496V4.5l3.737 3.738H33.3l3.485-3.486v6.992m0 7.75v7.345a11.78 11.78 0 0 1-11.802 11.63H13.088V35.32");
}

:global(.g2lobhhoe) {
  cx: 33.283px;
  cy: 15.596px;
  r: 1.873px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sjq238b6p) {
  cx: 33.283px;
  cy: 15.596px;
  r: 5.006px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.t-p8-o_xb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.088 22.334l-6.11 13.075s4.927 2.856 8.197-2.795l2.005.706s2.923-7.83-4.093-10.987Zm23.698 4.505l4.237 8.695s-4.13 1.943-7.018-1.232M18.816 38.47v5.03H21.6m3.384-5.03v5.03h2.782m1.842-22.169l-3.553 2.052V19.28Z");
}

:global(.uy5zjtbgn) {
  cx: 20.601px;
  cy: 15.596px;
  r: 1.873px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wtvflw8rc) {
  cx: 20.601px;
  cy: 15.596px;
  r: 5.006px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
