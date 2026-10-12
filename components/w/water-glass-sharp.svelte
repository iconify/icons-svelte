<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l9tu3cb2x"/><path class="a1ceucbha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:water-glass-sharp" {...props}></Icon>
<style>
:global(.a1ceucbha) {
  d: path("m7.5 9.5l2.25-1.125L12 9.5l2.25 1.125L16.5 9.5");
}

:global(.l9tu3cb2x) {
  d: path("M5.25 3.25h13.5L17 19.5l-.222 1.764L15 21.25H9l-1.778.014L7 19.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
