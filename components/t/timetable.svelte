<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="dt3j7ib_c"/><path class="q8t54gbbr"/><path class="gq9a447ri"/><path class="d0l1tlnzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:timetable" {...props}></Icon>
<style>
:global(.d0l1tlnzg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.88h8m-8 6.12h5m-5 6.13h8");
}

:global(.dt3j7ib_c) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.gq9a447ri) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 5.88h.01M5.75 12h.01m-.01 6.13h.01");
}

:global(.q8t54gbbr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9h18.5m-18.5 6h18.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
