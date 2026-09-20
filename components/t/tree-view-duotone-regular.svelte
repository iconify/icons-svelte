<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i1ubvjbeq"/><path class="vheinzb-r"/><path class="o3m44kb-z"/><path class="d3_4ghd5p"/><path class="xo_oskb7f"/><path class="ch9zmbran"/><path class="l8u0rbram"/><path class="q4yr01p9d"/><path class="i9dy6nm5t"/><path class="hfvs-qb2q"/><path class="p6_cldbhv"/><path class="z0r0_7bjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tree-view-duotone-regular" {...props}></Icon>
<style>
:global(.ch9zmbran) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 18h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d3_4ghd5p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hfvs-qb2q) {
  d: path("M11 11h10");
}

:global(.i1ubvjbeq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i9dy6nm5t) {
  d: path("M4 11h4");
}

:global(.l8u0rbram) {
  d: path("M4 4h17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o3m44kb-z) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p6_cldbhv) {
  d: path("M4 18h4");
}

:global(.q4yr01p9d) {
  d: path("M4 4v14");
}

:global(.vheinzb-r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xo_oskb7f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0r0_7bjh) {
  d: path("M11 18h10");
}

</style>
