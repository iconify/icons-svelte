<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="b6yjgkcjy"/><circle class="vqogbbbht"/><path class="r-cioob6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sniper" {...props}></Icon>
<style>
:global(.b6yjgkcjy) {
  cx: 24px;
  cy: 24px;
  r: 17.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r-cioob6o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24h14.183m0 1.591v-3.182M24 2.5v14.183m-1.591 0h3.182M45.5 24H31.317m0-1.591v3.182M24 45.5V31.317m1.591 0h-3.182");
}

:global(.vqogbbbht) {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
