<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ur7h5bb6e"/><path class="ba5kewmmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:segmented-control-duocolor-sharp" {...props}></Icon>
<style>
:global(.ba5kewmmn) {
  d: path("M3 6h18v12H3Zm14 6h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ur7h5bb6e) {
  stroke-opacity: 0.4;
  d: path("M6 9h6v6H6Z");
}

</style>
