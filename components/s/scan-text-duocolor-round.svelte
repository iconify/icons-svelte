<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="us36v70ur"/><path class="ly44l6qmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scan-text-duocolor-round" {...props}></Icon>
<style>
:global(.ly44l6qmn) {
  d: path("M3 7a4 4 0 0 1 4-4m10 0a4 4 0 0 1 4 4m0 10a4 4 0 0 1-4 4M7 21a4 4 0 0 1-4-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.us36v70ur) {
  stroke-opacity: 0.4;
  d: path("M7 8h10M7 12h10M7 16h6");
}

</style>
