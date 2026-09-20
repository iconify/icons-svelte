<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5ecbgu2w"/><path class="eljxzwbgp"/><path class="wkjitcbdw"/><path class="mcubrkb2y"/><path class="c4khiwgvb"/><path class="gi1v2vyju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wire-transfer-duotone-regular" {...props}></Icon>
<style>
:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.eljxzwbgp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gi1v2vyju) {
  d: path("M13.5 12.5 16 15l-2.5 2.5");
}

:global(.k5ecbgu2w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mcubrkb2y) {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wkjitcbdw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 12.5 16 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
