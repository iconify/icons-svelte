<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hdeeoveea"/><path class="z66xaz0er"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:usb-duocolor" {...props}></Icon>
<style>
:global(.hdeeoveea) {
  stroke-opacity: 0.4;
  d: path("M4 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m12-1a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1Zm-6 8a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z66xaz0er) {
  d: path("m9 6l3-3l3 3m-3-3v14m-4-5l4 4l4-4");
}

</style>
