<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="ybpxgwbdz"/><circle class="ry0hkee0e"/><circle class="vqogbbbht"/><path class="c3x9u-7wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sicmu-player" {...props}></Icon>
<style>
:global(.c3x9u-7wg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.385 22.015h4.74m-4.74 3.859h4.74m3.749-3.859h4.741m-4.741 3.859h4.741");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ry0hkee0e) {
  cx: 24px;
  cy: 24px;
  r: 2.593px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vqogbbbht) {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

:global(.ybpxgwbdz) {
  cx: 24.022px;
  cy: 24.011px;
  r: 6.988px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
