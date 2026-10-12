<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bklv9pdbp"/><path class="m0jp8_ilx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sunroof-sharp" {...props}></Icon>
<style>
:global(.bklv9pdbp) {
  d: path("M5.5 2.75h13v18.5h-13z");
}

:global(.m0jp8_ilx) {
  d: path("M7.75 7.5L12 6.134L16.25 7.5m-8 9.75L12 18.3l3.75-1.05M8.5 9.5h7v5h-7z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
