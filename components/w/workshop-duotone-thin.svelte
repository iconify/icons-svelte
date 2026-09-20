<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_hy4hbgg"/><path class="jm3xd8egv"/><path class="ssdglbbuh"/><path class="hiwkq4bpu"/><path class="oid8kdbim"/><path class="zugrvnb7t"/><path class="f5ieidcch"/><path class="q40roytdv"/><path class="gr2yy8pwl"/><path class="pkf-n2b8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:workshop-duotone-thin" {...props}></Icon>
<style>
:global(.f_hy4hbgg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f5ieidcch) {
  d: path("M5 13v8");
}

:global(.gr2yy8pwl) {
  d: path("M8 13V6h9v7");
}

:global(.hiwkq4bpu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 13V6h9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jm3xd8egv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 13v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oid8kdbim) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 6a2.5 2.5 0 0 1 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pkf-n2b8h) {
  d: path("M10 6a2.5 2.5 0 0 1 5 0");
}

:global(.q40roytdv) {
  d: path("M19 13v8");
}

:global(.ssdglbbuh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zugrvnb7t) {
  d: path("M2 13h20");
}

</style>
