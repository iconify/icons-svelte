<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oe3fan15t"/><path class="gq5zktbyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sausage-sharp" {...props}></Icon>
<style>
:global(.gq5zktbyq) {
  d: path("M9.61 14A12 12 0 0 1 14 9.61");
}

:global(.oe3fan15t) {
  d: path("M5.51 16.12A15 15 0 0 1 16.12 5.51a3 3 0 0 1 1.55 5.8a9 9 0 0 0-6.36 6.36a3 3 0 0 1-5.8-1.55Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
