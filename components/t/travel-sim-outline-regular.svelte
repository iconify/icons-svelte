<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="db30e8q5x"/><path class="d_4x3homz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:travel-sim-outline-regular" {...props}></Icon>
<style>
:global(.d_4x3homz) {
  d: path("M9 10h7v7H9Z");
}

:global(.db30e8q5x) {
  d: path("M6 3h10l3 3v15H6Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
