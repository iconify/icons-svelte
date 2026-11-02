<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c5ky8wsla"/><path class="h5b29obqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-3-duocolor" {...props}></Icon>
<style>
:global(.c5ky8wsla) {
  stroke-opacity: 0.4;
  d: path("M10 4v4m6 2v4m-9 2v4");
}

:global(.h5b29obqj) {
  d: path("M3 6h7m4 0h7M3 12h13m4 0h1M3 18h4m4 0h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
