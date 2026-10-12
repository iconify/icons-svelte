<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rgrs78b9k"/><path class="qc5p80bml"/><path class="f_uym8bal"/><path class="kx-a8669j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:slope-chart-sharp" {...props}></Icon>
<style>
:global(.f_uym8bal) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 14l14 4");
}

:global(.kx-a8669j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14h.01M19 18h.01");
}

:global(.qc5p80bml) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 8h.01M19 15h.01");
}

:global(.rgrs78b9k) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4v16M19 4v16M5 8l14 7");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
