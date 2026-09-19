<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="f3gvtsjrm"/><path class="wsbezhbuh"/><rect class="xzdjdd18l"/><path class="z52njs4_b"/><circle class="k6v9tbbgt"/><path class="q6t9wsbpo"/><path class="i9clfwm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:the-underground-blossom" {...props}></Icon>
<style>
:global(.f3gvtsjrm) {
  cx: 24px;
  cy: 23.587px;
  r: 8.706px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.k6v9tbbgt) {
  cx: 24px;
  cy: 23.587px;
  r: 1.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q6t9wsbpo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 22.447v-5.821m4.451 6.961H25.14m-2.588 8.706v1.501m2.896-1.501v1.501M30.36 42.5a6.36 6.36 0 0 0-12.72 0");
}

:global(.wsbezhbuh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.706 42.5a8.706 8.706 0 0 0-17.412 0");
}

:global(.xzdjdd18l) {
  width: 6.548px;
  height: 3.653px;
  x: 20.726px;
  y: 9.28px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.826px;
  ry: 1.826px;
}

:global(.z52njs4_b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.881v-3.368m-.798 0h1.596");
}

</style>
