<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nz1t31b3r"/><path class="xssdch4px"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:utensils-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nz1t31b3r) {
  stroke-opacity: 0.4;
  d: path("M3 3v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V3M7 3v18");
}

:global(.xssdch4px) {
  d: path("M21 14V3a5 5 0 0 0-5 5v4a2 2 0 0 0 2 2zm0 0v7");
}

</style>
