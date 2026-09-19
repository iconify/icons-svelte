<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="phoa8bcya"/><path class="l8n1hmb2e"/><rect class="ll6y--bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wooribank" {...props}></Icon>
<style>
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

:global(.l8n1hmb2e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.101 14H19a5 5 0 0 0 0 10h3.101m7.149 12v-6l3.975 6v-6m-12.45 0l-1.5 6l-1.5-6l-1.5 6l-1.5-6");
}

:global(.ll6y--bwo) {
  width: 3.975px;
  height: 6px;
  x: 22.65px;
  y: 30px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.988px;
  ry: 1.988px;
}

:global(.phoa8bcya) {
  cx: 27px;
  cy: 19px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
