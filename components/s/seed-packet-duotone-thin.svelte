<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6iop94az"/><path class="e04igbcxt"/><path class="uvugsybla"/><path class="d7j29trjs"/><path class="f8gsx7b5s"/><path class="p-3tqnbzb"/><path class="ak_t1bcfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:seed-packet-duotone-thin" {...props}></Icon>
<style>
:global(.ak_t1bcfw) {
  d: path("M14 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.d7j29trjs) {
  d: path("M6 4h12v16H6Z");
}

:global(.e04igbcxt) {
  fill: currentColor;
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.g6iop94az) {
  fill: currentColor;
  d: path("M6 4h12v16H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p-3tqnbzb) {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uvugsybla) {
  fill: currentColor;
  d: path("M14 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
