<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxj-8f9ba"/><path class="ukrud-btb"/><path class="vkfh0mhlc"/><path class="xykizhb4r"/><path class="nrhntbb4w"/><path class="kt4kzrb6r"/><path class="nvn647bwx"/><path class="p7tekpb9x"/><path class="tea8p3bbk"/><path class="ennto9b9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunlight-break-duotone-thin" {...props}></Icon>
<style>
:global(.dxj-8f9ba) {
  fill: currentColor;
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ennto9b9x) {
  d: path("M16 16h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kt4kzrb6r) {
  d: path("M5 21V4h8v17");
}

:global(.nrhntbb4w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 16h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nvn647bwx) {
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p7tekpb9x) {
  d: path("M16 8h5");
}

:global(.tea8p3bbk) {
  d: path("M16 12h5");
}

:global(.ukrud-btb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 21V4h8v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vkfh0mhlc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xykizhb4r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
