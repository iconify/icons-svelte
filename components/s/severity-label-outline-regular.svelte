<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w3hyiobto"/><path class="hgb-t7boy"/><path class="ykj59ccld"/><path class="udsnn3bwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:severity-label-outline-regular" {...props}></Icon>
<style>
:global(.hgb-t7boy) {
  d: path("M6 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.udsnn3bwn) {
  d: path("M9.5 17.5 12 15l2.5 2.5");
}

:global(.w3hyiobto) {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

:global(.ykj59ccld) {
  d: path("M9.5 13.5 12 11l2.5 2.5");
}

</style>
