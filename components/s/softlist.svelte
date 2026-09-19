<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ca51fsglw"/><path class="hja35gvsv"/><circle class="w1khqccew"/><circle class="wx79wgbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:softlist" {...props}></Icon>
<style>
:global(.ca51fsglw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 6.345h6.125l7.398 25.253h19.22L43.5 13.496H18.545");
}

:global(.hja35gvsv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.12 20.971l4.118 4.117l7.743-7.743");
}

:global(.w1khqccew) {
  cx: 19.886px;
  cy: 38.228px;
  r: 3.427px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wx79wgbnr) {
  cx: 34.241px;
  cy: 38.228px;
  r: 3.427px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
