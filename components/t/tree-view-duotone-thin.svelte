<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_ppl438w"/><path class="syitzib6b"/><path class="sy99v41wn"/><path class="djwq4xtov"/><path class="wcpm59bej"/><path class="wqay0w3wp"/><path class="l8u0rbram"/><path class="q4yr01p9d"/><path class="i9dy6nm5t"/><path class="hfvs-qb2q"/><path class="p6_cldbhv"/><path class="z0r0_7bjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tree-view-duotone-thin" {...props}></Icon>
<style>
:global(.djwq4xtov) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f_ppl438w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hfvs-qb2q) {
  d: path("M11 11h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9dy6nm5t) {
  d: path("M4 11h4");
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

:global(.sy99v41wn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.syitzib6b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wcpm59bej) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wqay0w3wp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 18h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0r0_7bjh) {
  d: path("M11 18h10");
}

</style>
