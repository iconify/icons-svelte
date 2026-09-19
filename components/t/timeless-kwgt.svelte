<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jm8-5lslf"/><circle class="f2yjju4lp"/><path class="j7p47fbty"/></g><path class="du_3-1byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:timeless-kwgt" {...props}></Icon>
<style>
:global(.du_3-1byw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.124 29.127a7.25 7.25 0 1 0-1.976-6.588l-.295 2.922a7.25 7.25 0 1 1-1.976-6.588");
}

:global(.f2yjju4lp) {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
}

:global(.j7p47fbty) {
  d: path("M36.654 34.492v8.016m3.692 0v-2.053L38.273 38.5l2.073-1.955v-2.053");
}

:global(.jm8-5lslf) {
  d: path("M33.43 43.327A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.4 21.4 0 0 1-2.174 9.431");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
