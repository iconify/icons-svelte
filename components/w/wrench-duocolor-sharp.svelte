<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rshakfbrf"/><path class="z_5r_ibhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wrench-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rshakfbrf) {
  stroke-opacity: 0.4;
  d: path("m12 15l-5 5a2.121 2.121 0 1 1-3-3l5-5");
}

:global(.z_5r_ibhj) {
  d: path("M9 12a5.385 5.385 0 0 1 7-7l-2 2l3 3l2-2a5.385 5.385 0 0 1-7 7");
}

</style>
