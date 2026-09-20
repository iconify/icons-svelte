<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsxmkkb6q"/><path class="mbt4yzbhr"/><path class="y_8jdcbuv"/><path class="l4avcpa0j"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="qvtmo6b3b"/><path class="a46bghb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-new-duotone-regular" {...props}></Icon>
<style>
:global(.a46bghb1i) {
  d: path("M18 10v6");
}

:global(.l4avcpa0j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mbt4yzbhr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oscmqi7_r) {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

:global(.qvtmo6b3b) {
  d: path("M15 13h6");
}

:global(.rsxmkkb6q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y_8jdcbuv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
