<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ivvufub2u"/><ellipse class="q1c780btn"/><ellipse class="eemiiacod"/><ellipse class="z7j9ecc7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tinc-app" {...props}></Icon>
<style>
:global(.eemiiacod) {
  cx: 30.547px;
  cy: 10.596px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.317px;
  ry: 5.356px;
}

:global(.ivvufub2u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.898 32.213l-4.066-16.426M15.926 31.265l16.149 4.664m-5.351-21.614L14.639 26.071");
}

:global(.q1c780btn) {
  cx: 37.183px;
  cy: 37.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.317px;
  ry: 5.356px;
}

:global(.z7j9ecc7n) {
  cx: 10.817px;
  cy: 29.789px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.317px;
  ry: 5.356px;
}

</style>
