<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwjllcbqv"/><path class="fi2ffwb2u"/><path class="wi4c4ehou"/><path class="xf05_3b3i"/><path class="caalxdxrm"/><path class="cwz65fbys"/><path class="fmr2g_bno"/><path class="hlnl_9cae"/><path class="llakqobuk"/><path class="nd30accfc"/><path class="e6tys9mkg"/><path class="nuz6-76is"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:task-graph-duotone-thin" {...props}></Icon>
<style>
:global(.caalxdxrm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cwz65fbys) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e6tys9mkg) {
  d: path("m7 16 4 -4");
}

:global(.fi2ffwb2u) {
  fill: currentColor;
  d: path("M3 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fmr2g_bno) {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gwjllcbqv) {
  fill: currentColor;
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hlnl_9cae) {
  d: path("M3 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.llakqobuk) {
  d: path("M11 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nd30accfc) {
  d: path("m7 8 4 4");
}

:global(.nuz6-76is) {
  d: path("M15 12h6");
}

:global(.wi4c4ehou) {
  fill: currentColor;
  d: path("M11 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xf05_3b3i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
