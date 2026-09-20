<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z4lviy67m"/><path class="anx8jnbhv"/><path class="h033mmb1s"/><path class="rlk52sj8y"/><path class="q1lsee9xq"/><path class="emo-jf0pj"/><path class="diaqyhfcp"/><path class="a97qfmbix"/><path class="pohupsbfv"/><path class="f99n1fbkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vet-duotone-bold" {...props}></Icon>
<style>
:global(.a97qfmbix) {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.anx8jnbhv) {
  fill: currentColor;
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.diaqyhfcp) {
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.emo-jf0pj) {
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.f99n1fbkg) {
  d: path("M16 7h6");
}

:global(.h033mmb1s) {
  fill: currentColor;
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pohupsbfv) {
  d: path("M19 4v6");
}

:global(.q1lsee9xq) {
  d: path("M11 19c-2.5 0 -4.5 -2 -4.5 -4s2 -3.5 4.5 -3.5 4.5 1.5 4.5 3.5 -2 4 -4.5 4");
}

:global(.rlk52sj8y) {
  fill: currentColor;
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z4lviy67m) {
  fill: currentColor;
  d: path("M11 19c-2.5 0 -4.5 -2 -4.5 -4s2 -3.5 4.5 -3.5 4.5 1.5 4.5 3.5 -2 4 -4.5 4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
