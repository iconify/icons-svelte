<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="wv6kc-pwf"/><circle class="tvszrwkla"/><circle class="gzcw-kt2d"/><circle class="h08g_4b2b"/><circle class="x6_sddbfy"/><circle class="yu2lg6_2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:synology-photos" {...props}></Icon>
<style>
:global(.gzcw-kt2d) {
  cx: 24px;
  cy: 11.906px;
  r: 9.406px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.h08g_4b2b) {
  cx: 13.527px;
  cy: 17.953px;
  r: 9.406px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tvszrwkla) {
  cx: 34.474px;
  cy: 17.953px;
  r: 9.406px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wv6kc-pwf) {
  cx: 34.474px;
  cy: 30.047px;
  r: 9.406px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.x6_sddbfy) {
  cx: 13.527px;
  cy: 30.047px;
  r: 9.406px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yu2lg6_2d) {
  cx: 24px;
  cy: 36.094px;
  r: 9.406px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
