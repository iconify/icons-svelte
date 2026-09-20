<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yt7qsrz-s"/><path class="r1yty139d"/><path class="jzeve79sx"/><path class="esz0ytbwn"/><path class="gr0pfvalr"/><path class="ymw3aibdo"/><path class="du_3_4tit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spa-duotone-regular" {...props}></Icon>
<style>
:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.esz0ytbwn) {
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.gr0pfvalr) {
  d: path("M9 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.r1yty139d) {
  fill: currentColor;
  d: path("M9 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yt7qsrz-s) {
  fill: currentColor;
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
