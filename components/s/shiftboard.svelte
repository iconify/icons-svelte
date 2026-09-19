<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yaqj32hvj"/><circle class="tj2bmz04y"/><circle class="xwyhn5m7a"/><path class="aq-mam02q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shiftboard" {...props}></Icon>
<style>
:global(.aq-mam02q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.815 36.905a5.15 5.15 0 0 1-6.31 3.643q0 0 0 0a5.15 5.15 0 0 1-3.642-6.31q0 0 0 0m6.51-23.143l-6.51 23.144M42.324 13.76l-6.51 23.145");
}

:global(.tj2bmz04y) {
  cx: 10.651px;
  cy: 12.427px;
  r: 5.151px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xwyhn5m7a) {
  cx: 10.651px;
  cy: 35.209px;
  r: 5.151px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yaqj32hvj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.373 11.095a5.151 5.151 0 1 1 9.951 2.666");
}

</style>
