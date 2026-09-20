<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yd020bcph"/><path class="f-4cwjbyj"/><path class="sboezp07x"/><path class="filuri95n"/><path class="p9fnnqwai"/><path class="g7rxpleju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-chill-duotone-regular" {...props}></Icon>
<style>
:global(.f-4cwjbyj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16h11a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.filuri95n) {
  d: path("M8 4v8m-4 0 8 -8");
}

:global(.g7rxpleju) {
  d: path("M4 20h14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p9fnnqwai) {
  d: path("M4 16h11a3 3 0 1 1 -3 3");
}

:global(.sboezp07x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yd020bcph) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4v8m-4 0 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
