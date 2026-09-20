<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="i-o0whboy"/><path class="a-bh3zwuf"/><path class="w7_ovbzxo"/><path class="t0kgu-35p"/><path class="bo51iypxr"/><path class="xz82qebme"/><path class="lz9b4vtgl"/><path class="glv5tabri"/><path class="x-fkne0xd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:typhoon-duotone-bold" {...props}></Icon>
<style>
:global(.a-bh3zwuf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.glv5tabri) {
  d: path("M19 12V5");
}

:global(.i-o0whboy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 12a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lz9b4vtgl) {
  d: path("M5 12a7 7 0 0 1 14 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t0kgu-35p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w7_ovbzxo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 12V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x-fkne0xd) {
  d: path("M5 12v7");
}

:global(.xz82qebme) {
  d: path("M19 12a7 7 0 0 1 -14 0");
}

</style>
