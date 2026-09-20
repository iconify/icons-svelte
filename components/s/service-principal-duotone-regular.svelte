<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="le41ikb_c"/><path class="gc7lymb4d"/><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="ok7fxmvnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:service-principal-duotone-regular" {...props}></Icon>
<style>
:global(.gc7lymb4d) {
  fill: currentColor;
  d: path("M9 14h6v6H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ia4sldbfw) {
  d: path("M3 21a9 9 0 0 1 18 0");
}

:global(.le41ikb_c) {
  fill: currentColor;
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ok7fxmvnu) {
  d: path("M9 14h6v6H9Z");
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
