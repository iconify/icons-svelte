<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="l6cd208_p"/><circle class="zn4syhbfs"/><ellipse class="ma0ec9w4o"/><path class="vixf7ccbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:stid" {...props}></Icon>
<style>
:global(.l6cd208_p) {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ma0ec9w4o) {
  cx: 12.814px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.314px;
  ry: 7.572px;
}

:global(.vixf7ccbc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h37v37h-37z");
}

:global(.zn4syhbfs) {
  cx: 17.547px;
  cy: 24px;
  r: 12.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
