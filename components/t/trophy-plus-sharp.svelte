<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="d4ss5kb_g"/><path class="vsgyv0b1w"/></g><path class="b1tcfcbpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trophy-plus-sharp" {...props}></Icon>
<style>
:global(.b1tcfcbpz) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 14.75v5.5m-2.75-2.75h5.5");
}

:global(.c7atyebze) {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.d4ss5kb_g) {
  d: path("M6.75 3.25h10.5v5.5a5.25 5.25 0 0 1-10.5 0Z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.utmrllbfo) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

:global(.vsgyv0b1w) {
  d: path("M6.75 5.25h-3.5v2c0 2.25 1.75 3.75 4.25 4m9.75-6h3.5v2c0 2.25-1.75 3.75-4.25 4");
}

:global(.wil2krbkc) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
