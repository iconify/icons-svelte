<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vu5qc50ra"/><path class="s72fzobki"/><path class="jrkx7rb6j"/><path class="rj24c2b0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shark" {...props}></Icon>
<style>
:global(.jrkx7rb6j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 12.75h.01");
}

:global(.rj24c2b0o) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 12v2.5");
}

:global(.s72fzobki) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9.75L12.25 5c.2-.35.7-.3.8.1L14 9.5");
}

:global(.vu5qc50ra) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13c2-3 7-4 11.25-3.5c2 .25 3.5 1 4.5 1.75L21 8.5L20 13l1 4.5l-2.5-2.75c-2 1.25-5 2-8.5 2S4 15.5 2.75 13");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
