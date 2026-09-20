<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="le41ikb_c"/><path class="asikq4-pf"/><path class="pemn838wn"/><path class="eu2so4bxo"/><path class="vi-y66bgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:worker-agent-duotone-regular" {...props}></Icon>
<style>
:global(.asikq4-pf) {
  fill: currentColor;
  d: path("M8 20.5A1.5 1.5 0 0 1 9.5 19h5a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-5A1.5 1.5 0 0 1 8 20.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.eu2so4bxo) {
  d: path("M7 16a5 5 0 0 1 10 0");
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

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vi-y66bgi) {
  d: path("M8 20.5A1.5 1.5 0 0 1 9.5 19h5a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-5A1.5 1.5 0 0 1 8 20.5");
}

</style>
