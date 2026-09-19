<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="iq2bi8q_x"/><path class="sq_ku0f0q"/><circle class="e0goa3kui"/><path class="i9clfwm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:trainline" {...props}></Icon>
<style>
:global(.e0goa3kui) {
  cx: 25.872px;
  cy: 29.306px;
  r: 0.75px;
  fill: currentColor;
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.iq2bi8q_x) {
  width: 4.792px;
  height: 6.374px;
  x: 18.692px;
  y: 31.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.396px;
  ry: 2.396px;
}

:global(.sq_ku0f0q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.484 31.784v6.374m4.776-3.978a2.396 2.396 0 0 1 2.396-2.396h0a2.396 2.396 0 0 1 2.396 2.396v3.978m-4.792-6.374v6.374M14.49 34.18a2.396 2.396 0 0 1 2.396-2.396h0m-2.397 0v6.374m-3.851-9.584v9.584m-1.673-6.374h3.347m13.56 0v6.374");
}

</style>
