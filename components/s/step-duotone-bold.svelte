<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yzszubbvg"/><path class="l2_jeopgb"/><path class="frqtfdihm"/><path class="s54fetbiu"/><path class="tbjorldxr"/><path class="doha7k7ng"/><path class="uhg14jb-c"/><path class="xh8-ghm1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-duotone-bold" {...props}></Icon>
<style>
:global(.doha7k7ng) {
  d: path("M10 11v7");
}

:global(.frqtfdihm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l2_jeopgb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s54fetbiu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tbjorldxr) {
  d: path("M3 18h7");
}

:global(.uhg14jb-c) {
  d: path("M10 11h7");
}

:global(.xh8-ghm1o) {
  d: path("M17 4v7");
}

:global(.yzszubbvg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
