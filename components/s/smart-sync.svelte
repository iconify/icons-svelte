<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-45 20.761 20.761)" class="e47y7ob8u"/><ellipse transform="rotate(-45 22.38 22.38)" class="qhm449bkp"/><ellipse transform="rotate(-45 24 24)" class="th-5rgbez"/><path class="f59jx8bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:smart-sync" {...props}></Icon>
<style>
:global(.e47y7ob8u) {
  cx: 20.761px;
  cy: 20.761px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 15.54px;
  ry: 13.522px;
}

:global(.f59jx8bjk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.168 34.045l-6.856-6.089");
}

:global(.qhm449bkp) {
  cx: 22.381px;
  cy: 22.381px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.172px;
  ry: 15.812px;
}

:global(.th-5rgbez) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 20.804px;
  ry: 18.102px;
}

</style>
