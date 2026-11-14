<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p9_bc8bri"/><path class="w0j9w5b9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:test-matrix" {...props}></Icon>
<style>
:global(.p9_bc8bri) {
  d: path("M2.5 2.5h19v19h-19Zm9.5 0v19M2.5 12h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w0j9w5b9z) {
  d: path("M5.25 7.5L6.75 9l2.5-3.5m6 9.75l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
