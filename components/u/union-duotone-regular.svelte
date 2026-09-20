<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w64svpbpc"/><path class="qdjgl5bua"/><path class="xers3_bpx"/><path class="on4ig8t5d"/><path class="smyhnv9tm"/><path class="ydl8e0r_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:union-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.on4ig8t5d) {
  d: path("M5 4v10");
}

:global(.qdjgl5bua) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 14a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.smyhnv9tm) {
  d: path("M19 14a7 7 0 0 1 -14 0");
}

:global(.w64svpbpc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xers3_bpx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ydl8e0r_x) {
  d: path("M19 4v10");
}

</style>
