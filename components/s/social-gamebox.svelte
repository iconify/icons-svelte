<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="w_5rkcc8u"/><circle class="koyxlmbei"/><circle class="i-x0qobct"/><circle class="x9eiz2b2k"/><circle class="vp125j8vw"/><circle class="fcubrmb1k"/><circle class="edi79mb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:social-gamebox" {...props}></Icon>
<style>
:global(.edi79mb8h) {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.fcubrmb1k) {
  cx: 24px;
  cy: 7px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i-x0qobct) {
  cx: 24px;
  cy: 41px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.koyxlmbei) {
  cx: 9.278px;
  cy: 32.5px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vp125j8vw) {
  cx: 38.722px;
  cy: 15.5px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.w_5rkcc8u) {
  cx: 9.278px;
  cy: 15.5px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.x9eiz2b2k) {
  cx: 38.722px;
  cy: 32.5px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
