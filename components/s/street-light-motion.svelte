<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bhu6c0qov"/><path class="h4hlfeb_x"/><path class="z5iasqbmm"/><path class="wm6xrqbhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:street-light-motion" {...props}></Icon>
<style>
:global(.bhu6c0qov) {
  d: path("M5 21.5V8a4.5 4.5 0 0 1 4.5-4.5H11");
}

:global(.h4hlfeb_x) {
  d: path("M10.5 3h7L16 6h-4ZM3 21.5h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wm6xrqbhl) {
  d: path("m18 16l-1 3m0 0l-1.5 2.5M17 19l2 2.5m-3.5-4L18 16l2 1.5");
}

:global(.z5iasqbmm) {
  fill: currentColor;
  d: path("M17.25 13.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
