<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l1of_swxy"/><circle class="ytopibb5c"/><path class="c3oztzbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:space-capsule-sharp" {...props}></Icon>
<style>
:global(.c3oztzbgy) {
  d: path("M4.25 18h15.5c-1.25 2-4.25 3.25-7.75 3.25S5.5 20 4.25 18Z");
}

:global(.l1of_swxy) {
  d: path("M10.75 3.25h3.75l.45 1.17l3.85 9.91l.45 1.17H4.75l.45-1.17l3.85-9.91l.45-1.17z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytopibb5c) {
  cx: 12px;
  cy: 10px;
  r: 2px;
}

</style>
