<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uttyj_yxy"/><path class="mv1mnhkel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:transmission-tower-duocolor-round" {...props}></Icon>
<style>
:global(.mv1mnhkel) {
  d: path("m6 21l4-12V7c0-1.28.36-2.36 1-3a1.414 1.414 0 0 1 2 0c.64.64 1 1.72 1 3v2l4 12M4 13a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uttyj_yxy) {
  stroke-opacity: 0.4;
  d: path("m9 12l3 6l3-6m-8 6h10");
}

</style>
