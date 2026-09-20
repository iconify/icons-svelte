<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zwjmk5b0j"/><path class="z3eyrdd0c"/><path class="sgqi5uicf"/><path class="jtt8g10_o"/><path class="ikiprn9sq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:status-bar-ui-duotone-regular" {...props}></Icon>
<style>
:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jtt8g10_o) {
  d: path("M9 10h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sgqi5uicf) {
  d: path("M10 5h4");
}

:global(.z3eyrdd0c) {
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.zwjmk5b0j) {
  fill: currentColor;
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
