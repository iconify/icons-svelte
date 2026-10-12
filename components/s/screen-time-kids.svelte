<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="vlvgqkbia"/><path class="g3h0tdpmx"/><path class="pd7oi69yu"/><circle class="lqa0robbd"/><path class="bcvszibcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:screen-time-kids" {...props}></Icon>
<style>
:global(.bcvszibcg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 13.25V15L19 16");
}

:global(.g3h0tdpmx) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 9.5h.01M9 9.5h.01");
}

:global(.lqa0robbd) {
  cx: 17.75px;
  cy: 15px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pd7oi69yu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.75a2 2 0 0 0 4 0");
}

:global(.vlvgqkbia) {
  width: 9.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
