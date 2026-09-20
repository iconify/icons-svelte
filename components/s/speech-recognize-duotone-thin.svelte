<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ueygn76rg"/><path class="kaf1fxbec"/><path class="il0fracwy"/><path class="y8jonpb2t"/><path class="xxobs597t"/><path class="nancp9ugm"/><path class="rgnpgnbjr"/><path class="fttf_kblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speech-recognize-duotone-thin" {...props}></Icon>
<style>
:global(.fttf_kblh) {
  d: path("M16 14h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.il0fracwy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 10h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kaf1fxbec) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.05 16.95a7 7 0 0 1 0 -9.9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nancp9ugm) {
  d: path("M5.05 16.95a7 7 0 0 1 0 -9.9");
}

:global(.rgnpgnbjr) {
  d: path("M16 10h5");
}

:global(.ueygn76rg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.88 14.12a3 3 0 0 1 0 -4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xxobs597t) {
  d: path("M7.88 14.12a3 3 0 0 1 0 -4.24");
}

:global(.y8jonpb2t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
