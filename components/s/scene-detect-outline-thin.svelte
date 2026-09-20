<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fp0jerb6p"/><path class="tqfrzx00u"/><path class="rx7vihb0q"/><path class="ir69e_bvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scene-detect-outline-thin" {...props}></Icon>
<style>
:global(.fp0jerb6p) {
  d: path("M10.5 6H13a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ir69e_bvd) {
  d: path("M11 8v8");
}

:global(.rx7vihb0q) {
  d: path("M7 8v8");
}

:global(.tqfrzx00u) {
  d: path("m19 10 3 -3v10l-3 -3Z");
}

</style>
