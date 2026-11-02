<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvopqdb9p"/><path class="u0zn-1eit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-sagittarius-duocolor" {...props}></Icon>
<style>
:global(.jvopqdb9p) {
  stroke-opacity: 0.4;
  d: path("M14 3h7v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u0zn-1eit) {
  d: path("M3 21L21 3M6 12l6 6");
}

</style>
