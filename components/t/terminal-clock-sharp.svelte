<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="pw7p-85ys"/><path class="nc0is4brm"/></g><circle class="is-iy812x"/><path class="sob-b5brj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:terminal-clock-sharp" {...props}></Icon>
<style>
:global(.c7atyebze) {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.is-iy812x) {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nc0is4brm) {
  d: path("m7.25 9.25l3 2.75l-3 2.75");
}

:global(.pw7p-85ys) {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.sob-b5brj) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 15.75v1.75l1.25 1");
}

:global(.utmrllbfo) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

:global(.wil2krbkc) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
