<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ii4t72bxj"/><path class="j1f41eokg"/><path class="ignqnzbqn"/><path class="pnc_2386u"/><path class="kti327bux"/><path class="kamdbib6v"/><path class="pmuiqo95v"/><path class="kt4_ogrrr"/><path class="hgjyjobhk"/><path class="gvpticbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:waist-measure-duotone-thin" {...props}></Icon>
<style>
:global(.gvpticbjc) {
  d: path("M18 7v4");
}

:global(.hgjyjobhk) {
  d: path("M12 7v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ignqnzbqn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ii4t72bxj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j1f41eokg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.kt4_ogrrr) {
  d: path("M6 7v4");
}

:global(.kti327bux) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.pnc_2386u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
