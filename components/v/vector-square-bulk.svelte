<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gwhycgb1s"/><path class="rmd63zbjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:vector-square-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gwhycgb1s) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 5v2h2v10h-2v2H7v-2H5V7h2V5Z");
}

:global(.rmd63zbjn) {
  d: path("M2 4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2h8a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2v8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2H8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2V8a2 2 0 0 1-2-2Zm4 4v8a2 2 0 0 1 2 2h8a2 2 0 0 1 2-2V8a2 2 0 0 1-2-2H8a2 2 0 0 1-2 2");
}

</style>
