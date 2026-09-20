<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qx40f8bin"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="dwto70uro"/><path class="nonq38brg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-pin-duotone-regular" {...props}></Icon>
<style>
:global(.dwto70uro) {
  d: path("M15 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nonq38brg) {
  d: path("M18 13v3.5");
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

:global(.qx40f8bin) {
  fill: currentColor;
  d: path("M15 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
