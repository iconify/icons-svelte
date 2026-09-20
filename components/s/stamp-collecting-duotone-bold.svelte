<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sx2hp3luj"/><path class="mi3-krpeu"/><path class="fy9mjw90d"/><path class="gc6g55g4b"/><path class="v-5f_sb8n"/><path class="ak36m6b8g"/><path class="f4nuxtbsp"/><path class="o9j8_ob8u"/><path class="ozywi-m1p"/><path class="elm0fn4gd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stamp-collecting-duotone-bold" {...props}></Icon>
<style>
:global(.ak36m6b8g) {
  d: path("M4 5h16v14H4Zm0 0");
}

:global(.elm0fn4gd) {
  d: path("M19 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.f4nuxtbsp) {
  d: path("M8 9h8v6H8Z");
}

:global(.fy9mjw90d) {
  fill: currentColor;
  d: path("M3 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gc6g55g4b) {
  fill: currentColor;
  d: path("M3 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mi3-krpeu) {
  fill: currentColor;
  d: path("M8 9h8v6H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o9j8_ob8u) {
  d: path("M3 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ozywi-m1p) {
  d: path("M3 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sx2hp3luj) {
  fill: currentColor;
  d: path("M4 5h16v14H4Zm0 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.v-5f_sb8n) {
  fill: currentColor;
  d: path("M19 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
