<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p52u7fomt"/><path class="wiz9_z3fs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:video-off-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p52u7fomt) {
  stroke-opacity: 0.4;
  d: path("m2 3l19 19");
}

:global(.wiz9_z3fs) {
  d: path("M14.647 15.647A4 4 0 0 1 11 18H7a4 4 0 0 1-4-4v-4a4 4 0 0 1 2.354-3.646M11 6a4 4 0 0 1 4 4m0 0l2-1c1.838-.919 4 .162 4 2v2c0 .828-.44 1.503-1.09 1.91");
}

</style>
