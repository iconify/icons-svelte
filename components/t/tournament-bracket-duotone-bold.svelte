<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rxwr8htky"/><path class="foytbhsts"/><path class="sj6dfcbdj"/><path class="yp_l0abrr"/><path class="rdhgnbc4d"/><path class="qno8l4b9z"/><path class="nuz6-76is"/><path class="l3ca9u8kt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tournament-bracket-duotone-bold" {...props}></Icon>
<style>
:global(.foytbhsts) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h6v7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l3ca9u8kt) {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nuz6-76is) {
  d: path("M15 12h6");
}

:global(.qno8l4b9z) {
  d: path("M3 19h6v-7");
}

:global(.rdhgnbc4d) {
  d: path("M3 5h6v7h6");
}

:global(.rxwr8htky) {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.sj6dfcbdj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h6v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yp_l0abrr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
