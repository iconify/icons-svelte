<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c2xrbabwq"/><circle class="gmmpe7bsl"/><circle class="nrlvaw3io"/><path class="drp0idboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:voicemail" {...props}></Icon>
<style>
:global(.c2xrbabwq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

:global(.drp0idboy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.561 30.561h16.878");
}

:global(.gmmpe7bsl) {
  cx: 15.561px;
  cy: 24px;
  r: 6.561px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nrlvaw3io) {
  cx: 32.439px;
  cy: 24px;
  r: 6.561px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
