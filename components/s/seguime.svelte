<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="q04ibibrl"/><circle class="ydg-435rt"/><path class="c9bjc-bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:seguime" {...props}></Icon>
<style>
:global(.c9bjc-bxk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24h5.375M24 7.875V2.5M40.125 24H45.5M24 40.125V45.5");
}

:global(.q04ibibrl) {
  cx: 24px;
  cy: 24px;
  r: 16.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ydg-435rt) {
  cx: 24px;
  cy: 24px;
  r: 6.271px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
