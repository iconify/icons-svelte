<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jec9yzbnr"/><rect class="bt_yqrbkd"/><rect class="d-qfemb6k"/><rect class="x3jdi7dwf"/><rect class="bd4ymsbye"/><rect class="o0v9otb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:themes-app-icons" {...props}></Icon>
<style>
:global(.bd4ymsbye) {
  width: 6.452px;
  height: 6.452px;
  x: 36.048px;
  y: 15.548px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.bt_yqrbkd) {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.d-qfemb6k) {
  width: 6.452px;
  height: 6.452px;
  x: 26px;
  y: 15.548px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.jec9yzbnr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 26h-33a2 2 0 0 0-2 2v12.5a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2V28a2 2 0 0 0-2-2");
}

:global(.o0v9otb3b) {
  width: 6.452px;
  height: 6.452px;
  x: 36.048px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.x3jdi7dwf) {
  width: 6.452px;
  height: 6.452px;
  x: 26px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
