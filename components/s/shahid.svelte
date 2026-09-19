<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="p097jmb0r"/><circle class="uxxq3nb8o"/><circle class="tdc75hbwc"/><path class="qtfjx4buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shahid" {...props}></Icon>
<style>
:global(.p097jmb0r) {
  cx: 9.102px;
  cy: 15.07px;
  r: 4.602px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qtfjx4buw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.337 33.873V26.43h37.491v11.22h-7.802v-3.857c-9.886.02-19.844.03-29.689.079Z");
}

:global(.tdc75hbwc) {
  cx: 38.898px;
  cy: 14.979px;
  r: 4.602px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.uxxq3nb8o) {
  cx: 23.913px;
  cy: 14.95px;
  r: 4.602px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
