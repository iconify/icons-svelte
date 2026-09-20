<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxdgzqbaj"/><path class="cw9gc0jvg"/><path class="ld7zhcybq"/><path class="lehy25blz"/><path class="g6gycjbtj"/><path class="f7gzzcj6n"/><path class="t1sjjacis"/><path class="veni6hbgn"/><path class="u_41jqbcx"/><path class="epoh96bbt"/><path class="zr69sp0ly"/><path class="i6r2d3rzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:service-map-duotone-thin" {...props}></Icon>
<style>
:global(.cw9gc0jvg) {
  fill: currentColor;
  d: path("M16 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.epoh96bbt) {
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f7gzzcj6n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16.5 7.5 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g6gycjbtj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7.5 7.5 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6r2d3rzf) {
  d: path("m16.5 7.5 -9 9");
}

:global(.ld7zhcybq) {
  fill: currentColor;
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lehy25blz) {
  fill: currentColor;
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t1sjjacis) {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.u_41jqbcx) {
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.veni6hbgn) {
  d: path("M16 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vxdgzqbaj) {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zr69sp0ly) {
  d: path("m7.5 7.5 9 9");
}

</style>
