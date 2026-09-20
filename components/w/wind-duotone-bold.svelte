<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ck0b4vbcx"/><path class="ihr390gsy"/><path class="paev_nbee"/><path class="afxv9_b8a"/><path class="oq5d88tuy"/><path class="x199_yb0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-duotone-bold" {...props}></Icon>
<style>
:global(.afxv9_b8a) {
  d: path("M3 7h12a3 3 0 1 0 -3 -3");
}

:global(.ck0b4vbcx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h12a3 3 0 1 0 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ihr390gsy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oq5d88tuy) {
  d: path("M3 12h15");
}

:global(.paev_nbee) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h11a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x199_yb0z) {
  d: path("M3 17h11a3 3 0 1 1 -3 3");
}

</style>
