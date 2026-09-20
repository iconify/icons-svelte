<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p8iop6bwz"/><path class="vugti51pk"/><path class="ow_8zyeff"/><path class="jujxaqbqg"/><path class="q6rh9u55e"/><path class="v_a3lnirg"/><path class="lvtw3tv7j"/><path class="c-xj8zban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ski-run-duotone-regular" {...props}></Icon>
<style>
:global(.c-xj8zban) {
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jujxaqbqg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 21 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lvtw3tv7j) {
  d: path("m16 21 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ow_8zyeff) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21 18 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8iop6bwz) {
  fill: currentColor;
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q6rh9u55e) {
  d: path("M3 18 15 6");
}

:global(.v_a3lnirg) {
  d: path("M6 21 18 9");
}

:global(.vugti51pk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18 15 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
