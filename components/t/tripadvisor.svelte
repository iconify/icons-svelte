<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="dwy0d7bed"/><circle class="kk3mgebfs"/><circle class="r___gttut"/><circle class="xzv_oworn"/><path class="zy297ec-c"/><path class="ao8uy8vhd"/><path class="th_--p9po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tripadvisor" {...props}></Icon>
<style>
:global(.ao8uy8vhd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.642 19.046C35.455 13.859 30.096 12.313 24 12.313c-6.095 0-11.455 1.546-16.642 6.732m19.5 13.785L24 35.688l-2.858-2.858");
}

:global(.dwy0d7bed) {
  cx: 14.25px;
  cy: 25.938px;
  r: 9.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kk3mgebfs) {
  cx: 33.75px;
  cy: 25.938px;
  r: 9.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r___gttut) {
  cx: 14.25px;
  cy: 25.938px;
  r: 3.079px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.th_--p9po) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.271 16.188H43.5l-2.858 2.858");
}

:global(.xzv_oworn) {
  cx: 33.75px;
  cy: 25.938px;
  r: 3.079px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zy297ec-c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.729 16.188H4.5l2.858 2.858");
}

</style>
