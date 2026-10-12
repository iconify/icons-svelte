<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="soowh948y"/><path class="d65b46k-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stitch-clip-sharp" {...props}></Icon>
<style>
:global(.d65b46k-y) {
  d: path("M5.25 10.25v3.5L8 12Zm11 0v3.5L19 12Z");
}

:global(.soowh948y) {
  d: path("M2.75 6.25h7.5v11.5h-7.5zm11 0h7.5v11.5h-7.5zM10.25 12h3.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
