<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="cd6712-qp"/><circle class="vb-gl3bpi"/><circle class="wq0cpwmen"/><circle class="wv5ca1btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ukg-pro-classic" {...props}></Icon>
<style>
:global(.cd6712-qp) {
  cx: 24px;
  cy: 24px;
  r: 4.3px;
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

:global(.vb-gl3bpi) {
  cx: 11.838px;
  cy: 36.162px;
  r: 4.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wq0cpwmen) {
  cx: 36.162px;
  cy: 36.162px;
  r: 4.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wv5ca1btb) {
  cx: 24px;
  cy: 24px;
  r: 12.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
