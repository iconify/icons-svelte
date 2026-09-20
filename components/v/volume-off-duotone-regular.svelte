<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jhn2mxbpk"/><path class="jmjqszbgk"/><path class="ljir_j9fp"/><path class="ggag34r5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:volume-off-duotone-regular" {...props}></Icon>
<style>
:global(.ggag34r5e) {
  d: path("m21 9 -5 5");
}

:global(.jhn2mxbpk) {
  fill: currentColor;
  d: path("M8 9H3v6h5l5 5V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jmjqszbgk) {
  d: path("M8 9H3v6h5l5 5V4Z");
}

:global(.ljir_j9fp) {
  d: path("m16 9 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
