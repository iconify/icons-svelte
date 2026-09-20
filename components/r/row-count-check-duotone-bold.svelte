<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g4xoo_izn"/><path class="ppqzlq-xl"/><path class="h7mcmwbmh"/><path class="qltayccdm"/><path class="rsy-y08mq"/><path class="sixdm4bhp"/><path class="sgz4g8k3l"/><path class="ievtq1brs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:row-count-check-duotone-bold" {...props}></Icon>
<style>
:global(.g4xoo_izn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7mcmwbmh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ievtq1brs) {
  d: path("M14.5 17.5 17 20l4.5 -4.5");
}

:global(.ppqzlq-xl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qltayccdm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 17.5 17 20l4.5 -4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rsy-y08mq) {
  d: path("M3 4h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sgz4g8k3l) {
  d: path("M3 14h14");
}

:global(.sixdm4bhp) {
  d: path("M3 9h14");
}

</style>
