<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w1oesmbrj"/><path class="iyv9vnbio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:standing-desk-duocolor-round" {...props}></Icon>
<style>
:global(.iyv9vnbio) {
  d: path("M3 20a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4M11 6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2Zm5 6v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w1oesmbrj) {
  stroke-opacity: 0.4;
  d: path("m3 6l2-2l2 2m-4 4l2 2l2-2");
}

</style>
