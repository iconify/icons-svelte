<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hpwoyl28q"/><path class="m520t0blj"/><path class="v3tixu15n"/><path class="cfc1y5xko"/><path class="tbjorldxr"/><path class="doha7k7ng"/><path class="uhg14jb-c"/><path class="xh8-ghm1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-duotone-thin" {...props}></Icon>
<style>
:global(.cfc1y5xko) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 4v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.doha7k7ng) {
  d: path("M10 11v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hpwoyl28q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m520t0blj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tbjorldxr) {
  d: path("M3 18h7");
}

:global(.uhg14jb-c) {
  d: path("M10 11h7");
}

:global(.v3tixu15n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xh8-ghm1o) {
  d: path("M17 4v7");
}

</style>
