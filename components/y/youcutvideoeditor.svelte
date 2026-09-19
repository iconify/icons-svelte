<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="l3ytg0xyw"/><circle class="cp-sir2lc"/><circle class="zig5s2b3o"/><circle class="mnobhb5fi"/><circle class="ka2p__b5e"/><circle class="xtaxzuq0r"/><circle class="l-nwi0b7f"/><circle class="tf45bebck"/><circle class="u-h4rhbgo"/><path class="j61n5-bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:youcutvideoeditor" {...props}></Icon>
<style>
:global(.cp-sir2lc) {
  cx: 34.338px;
  cy: 34.882px;
  r: 7.618px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.j61n5-bgw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.747 28.027L12.574 9.853h-6.53L27.482 31.29m-4.026-4.025L12.574 38.147h-6.53L20.191 24m3.265-3.265l4.026-4.026M26.72 24l4.027-4.027");
}

:global(.ka2p__b5e) {
  cx: 36.841px;
  cy: 31.4px;
  r: 1.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.l-nwi0b7f) {
  cx: 34.338px;
  cy: 39.127px;
  r: 1.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.l3ytg0xyw) {
  cx: 34.338px;
  cy: 13.118px;
  r: 7.618px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mnobhb5fi) {
  cx: 34.338px;
  cy: 34.882px;
  r: 0.75px;
  fill: currentColor;
}

:global(.tf45bebck) {
  cx: 30.203px;
  cy: 36.188px;
  r: 1.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u-h4rhbgo) {
  cx: 23.456px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

:global(.xtaxzuq0r) {
  cx: 38.474px;
  cy: 36.188px;
  r: 1.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zig5s2b3o) {
  cx: 31.835px;
  cy: 31.509px;
  r: 1.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
