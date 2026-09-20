<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tu3bv3eig"/><path class="kst6m0v6a"/><path class="yoftwf7ei"/><path class="qzpg-bc7o"/><path class="ic_pehd5a"/><path class="ofzwylwbi"/><path class="ejtyvbbdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:water-meter-duotone-bold" {...props}></Icon>
<style>
:global(.ejtyvbbdg) {
  d: path("M17 15v4");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.kst6m0v6a) {
  fill: currentColor;
  d: path("m12 6 2 2a2.8 2.8 0 1 1 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ofzwylwbi) {
  d: path("M7 15v4");
}

:global(.qzpg-bc7o) {
  d: path("m12 6 2 2a2.8 2.8 0 1 1 -4 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tu3bv3eig) {
  fill: currentColor;
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yoftwf7ei) {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
