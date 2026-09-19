<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="k_573kbyb"/><path class="riswa0bgg"/><circle class="ney6pwu7c"/><circle class="lkp16ccie"/><circle class="npusgdy0n"/><path class="mt6c5myog"/><circle class="z9ado3b3s"/><circle class="gxhlbrhdb"/><circle class="ooru31b3b"/><path class="wx-xlebfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sequoia" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gxhlbrhdb) {
  cx: 33.116px;
  cy: 22.096px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k_573kbyb) {
  cx: 24px;
  cy: 10.43px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lkp16ccie) {
  cx: 14.884px;
  cy: 24.969px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mt6c5myog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.457 19.044H24m-7.069 5.925H24m-2.543 5.925H24");
}

:global(.ney6pwu7c) {
  cx: 19.411px;
  cy: 19.044px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.npusgdy0n) {
  cx: 19.411px;
  cy: 30.894px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ooru31b3b) {
  cx: 28.589px;
  cy: 28.02px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.riswa0bgg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5V12.477");
}

:global(.wx-xlebfk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.543 16.171H24m7.069 5.925H24m2.543 5.924H24");
}

:global(.z9ado3b3s) {
  cx: 28.589px;
  cy: 16.171px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
