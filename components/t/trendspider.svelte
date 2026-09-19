<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="gp5xdbcvx"/><circle class="le3xc0xnj"/><circle class="eibpcwb4w"/><circle class="g7glkeb4y"/><circle class="o5b6jab_v"/><circle class="c00t50vyf"/><circle class="qzjcdzrma"/><circle class="hypjuubbc"/><path class="i54b24m6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:trendspider" {...props}></Icon>
<style>
:global(.c00t50vyf) {
  cx: 20.5px;
  cy: 25.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.eibpcwb4w) {
  cx: 33.5px;
  cy: 10.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.g7glkeb4y) {
  cx: 15.5px;
  cy: 37.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gp5xdbcvx) {
  cx: 39.5px;
  cy: 33.6px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hypjuubbc) {
  cx: 15.75px;
  cy: 14px;
  r: 2.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i54b24m6v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.8 16.542l2.746 6.648m-2.892 11.54l2.885-6.922m3.273-1.356l3.645 1.5m5.062 2.151l5.233 2.293M22.076 23.56l3.347-4.12m3.278-3.772l2.757-2.97");
}

:global(.le3xc0xnj) {
  cx: 29px;
  cy: 29px;
  r: 2.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.o5b6jab_v) {
  cx: 8.5px;
  cy: 25px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qzjcdzrma) {
  cx: 27px;
  cy: 17.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
