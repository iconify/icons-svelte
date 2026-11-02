<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gncq5yvtt"/><path class="j-wxgjbtz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sunset-duocolor" {...props}></Icon>
<style>
:global(.gncq5yvtt) {
  stroke-opacity: 0.4;
  d: path("m9 7l3 3l3-3m-3 3V3");
}

:global(.j-wxgjbtz) {
  d: path("M9 17a3 3 0 0 1 6 0M3 17h2m14 0h2M3 21h18M5 10l2 2m12-2l-2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
