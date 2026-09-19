<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vu1hi392y"/><circle class="qkjb0ohzr"/><circle class="tt8r24b3y"/><circle class="dx5ffubpx"/><circle class="wb7tg1anr"/><path class="a_gb2_b-k"/><path class="bb_5ozd7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sentio-desktop" {...props}></Icon>
<style>
:global(.a_gb2_b-k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.701 28.028l-11.114-6.417v-4.778L24 9.668l11.114 6.417");
}

:global(.bb_5ozd7f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.299 19.972l11.114 6.417v4.778L24 38.332l-11.114-6.416");
}

:global(.dx5ffubpx) {
  cx: 24px;
  cy: 28.778px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qkjb0ohzr) {
  cx: 36.413px;
  cy: 16.833px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tt8r24b3y) {
  cx: 24px;
  cy: 19.222px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vu1hi392y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22 3.035l-15.156 8.75a4 4 0 0 0-2 3.465v17.5a4 4 0 0 0 2 3.465L22 44.965a4 4 0 0 0 4 0l15.156-8.75a4 4 0 0 0 2-3.465v-17.5a4 4 0 0 0-2-3.465L26 3.035a4 4 0 0 0-4 0");
}

:global(.wb7tg1anr) {
  cx: 11.587px;
  cy: 31.167px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
