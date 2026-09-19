<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b151vsb8l"/><path class="a9q3fgb0s"/><circle class="an1ihdqan"/><circle class="ci694hbvt"/><circle class="k3nbzebuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:simple-sharing" {...props}></Icon>
<style>
:global(.a9q3fgb0s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.754 32.98l4.217-4.217l-4.217-4.217");
}

:global(.an1ihdqan) {
  cx: 12.099px;
  cy: 28.763px;
  r: 1.007px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.b151vsb8l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.438 23.281a11.339 11.339 0 0 0-22.665 0a6.206 6.206 0 0 0 .15 12.41h22.365a6.206 6.206 0 0 0 .15-12.41");
}

:global(.ci694hbvt) {
  cx: 5.507px;
  cy: 28.763px;
  r: 1.007px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k3nbzebuo) {
  cx: 17.93px;
  cy: 28.763px;
  r: 1.007px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
