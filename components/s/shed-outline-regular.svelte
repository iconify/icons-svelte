<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a6e_o0bju"/><path class="sv8lhpyik"/><path class="qkzndobnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shed-outline-regular" {...props}></Icon>
<style>
:global(.a6e_o0bju) {
  d: path("m3 11 9 -9 9 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qkzndobnz) {
  d: path("M10 20v-6h4v6");
}

:global(.sv8lhpyik) {
  d: path("M5 11v9h14v-9");
}

</style>
