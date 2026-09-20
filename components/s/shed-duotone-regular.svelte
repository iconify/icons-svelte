<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqqiwbo9y"/><path class="t2kt2djuj"/><path class="c0e0zxbrd"/><path class="a6e_o0bju"/><path class="sv8lhpyik"/><path class="qkzndobnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shed-duotone-regular" {...props}></Icon>
<style>
:global(.a6e_o0bju) {
  d: path("m3 11 9 -9 9 9");
}

:global(.c0e0zxbrd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 20v-6h4v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pqqiwbo9y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 11 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qkzndobnz) {
  d: path("M10 20v-6h4v6");
}

:global(.sv8lhpyik) {
  d: path("M5 11v9h14v-9");
}

:global(.t2kt2djuj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11v9h14v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
