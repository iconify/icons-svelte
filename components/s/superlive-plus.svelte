<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="brxpxfbzn"/><circle class="hwh27ic0k"/><circle class="kgeehyy8x"/><path class="yekx0zw1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:superlive-plus" {...props}></Icon>
<style>
:global(.brxpxfbzn) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

:global(.hwh27ic0k) {
  cx: 23.958px;
  cy: 24px;
  r: 14.266px;
}

:global(.kgeehyy8x) {
  cx: 24.042px;
  cy: 24.084px;
  r: 8.601px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yekx0zw1a) {
  d: path("M29.51 26.709a6.08 6.08 0 0 1-3.447 3.072m-7.899-7.928a6.2 6.2 0 0 1 6.335-4.091");
}

</style>
