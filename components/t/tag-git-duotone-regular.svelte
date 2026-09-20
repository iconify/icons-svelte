<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ylas06exf"/><path class="ugj52-r_t"/><path class="c4e1y7wvc"/><path class="g5wa7kbrn"/><path class="r-3a_wp2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tag-git-duotone-regular" {...props}></Icon>
<style>
:global(.c4e1y7wvc) {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.g5wa7kbrn) {
  d: path("M8 12h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r-3a_wp2m) {
  d: path("M13 8h5l4 4 -4 4h-5Z");
}

:global(.ugj52-r_t) {
  fill: currentColor;
  d: path("M13 8h5l4 4 -4 4h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ylas06exf) {
  fill: currentColor;
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
