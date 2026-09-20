<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p3nbe8bvt"/><path class="vyhobobtn"/><path class="mxpxejnja"/><path class="su9etdbad"/><path class="uidmmjb0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:threat-hunt-duotone-regular" {...props}></Icon>
<style>
:global(.mxpxejnja) {
  d: path("M3 5h8v6l-4 4 -4 -4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3nbe8bvt) {
  fill: currentColor;
  d: path("M3 5h8v6l-4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.su9etdbad) {
  d: path("M14 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

:global(.uidmmjb0u) {
  d: path("m20 12.5 2 2");
}

:global(.vyhobobtn) {
  fill: currentColor;
  d: path("M14 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
