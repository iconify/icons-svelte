<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b7rzcxbgu"/><path class="iz9aapgxw"/><path class="cckr0sbve"/><path class="yn_8bkf-e"/><path class="g3a305brv"/><path class="xjm2gaclr"/><path class="l8u0rbram"/><path class="q4yr01p9d"/><path class="i9dy6nm5t"/><path class="hfvs-qb2q"/><path class="p6_cldbhv"/><path class="z0r0_7bjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tree-view-duotone-bold" {...props}></Icon>
<style>
:global(.b7rzcxbgu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cckr0sbve) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g3a305brv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hfvs-qb2q) {
  d: path("M11 11h10");
}

:global(.i9dy6nm5t) {
  d: path("M4 11h4");
}

:global(.iz9aapgxw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8u0rbram) {
  d: path("M4 4h17");
}

:global(.p6_cldbhv) {
  d: path("M4 18h4");
}

:global(.q4yr01p9d) {
  d: path("M4 4v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xjm2gaclr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 18h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yn_8bkf-e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0r0_7bjh) {
  d: path("M11 18h10");
}

</style>
