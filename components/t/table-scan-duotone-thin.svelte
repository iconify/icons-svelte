<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xf1regb7a"/><path class="f3iw3wbzh"/><path class="w1z4wnfys"/><path class="kamdbib6v"/><path class="wlpqxdb6z"/><path class="uduptbc9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:table-scan-duotone-thin" {...props}></Icon>
<style>
:global(.f3iw3wbzh) {
  fill: currentColor;
  d: path("M8 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.uduptbc9i) {
  d: path("m13 20 2 2");
}

:global(.w1z4wnfys) {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.wlpqxdb6z) {
  d: path("M8 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.xf1regb7a) {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
