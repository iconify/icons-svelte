<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asqszxb9j"/><path class="moitg-beq"/><path class="dkxdfrn3s"/><path class="wtr271uqu"/><path class="bt_2bvgpa"/><path class="ozi-k-boi"/><path class="n-7t0yb1r"/><path class="rkhcgsbdl"/><path class="vxuzbkitn"/><path class="z1zyir08z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shelf-duotone-thin" {...props}></Icon>
<style>
:global(.asqszxb9j) {
  fill: currentColor;
  d: path("M5.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dkxdfrn3s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.moitg-beq) {
  fill: currentColor;
  d: path("M14.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.vxuzbkitn) {
  d: path("M5.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wtr271uqu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z1zyir08z) {
  d: path("M14.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
