<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tbjorldxr"/><path class="doha7k7ng"/><path class="uhg14jb-c"/><path class="xh8-ghm1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-outline-regular" {...props}></Icon>
<style>
:global(.doha7k7ng) {
  d: path("M10 11v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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

</style>
