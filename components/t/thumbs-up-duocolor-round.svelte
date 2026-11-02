<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nwwpoi3_a"/><path class="x-x_tvbhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thumbs-up-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nwwpoi3_a) {
  stroke-opacity: 0.4;
  d: path("M7 10H5a2 2 0 0 0-2 2v7a2 2 0 1 0 4 0z");
}

:global(.x-x_tvbhr) {
  d: path("M7 10a4 4 0 0 0 4-4V5a2 2 0 1 1 4 0v3a2 2 0 0 0 2 2h1a3 3 0 0 1 3 3v1l-1 5c-.233 1.163-1.488 2-3 2H9a2 2 0 0 1-2-2");
}

</style>
