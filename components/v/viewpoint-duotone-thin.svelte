<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fsuht_b8c"/><path class="bx2r9yb9w"/><path class="vosnu143j"/><path class="oze4upblc"/><path class="acyg6nb1v"/><path class="idhymedkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:viewpoint-duotone-thin" {...props}></Icon>
<style>
:global(.acyg6nb1v) {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bx2r9yb9w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.36 5.95a6 6 0 0 1 11.28 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fsuht_b8c) {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.idhymedkk) {
  d: path("m2 20 6 -6 3 3 5 -5 5 5");
}

:global(.oze4upblc) {
  d: path("M6.36 5.95a6 6 0 0 1 11.28 0");
}

:global(.vosnu143j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 20 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
