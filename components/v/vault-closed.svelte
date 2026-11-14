<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="phvp-0bsd"/><path class="vg2c2yk9x"/><path class="k2b4-rtaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vault-closed" {...props}></Icon>
<style>
:global(.k2b4-rtaj) {
  d: path("M11 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5-1.5V6m1.25 6.75l4 2.25m-6.5-2.25l-4 2.25");
}

:global(.phvp-0bsd) {
  d: path("M3.75 12a8.75 8.75 0 1 0 17.5 0a8.75 8.75 0 1 0-17.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vg2c2yk9x) {
  d: path("M2 7.25h2.5V10H2ZM2 14h2.5v2.75H2Zm6.25-2a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

</style>
