<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g6hskxb9z"/><path class="myt_b32pc"/><path class="y29zmn0-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shellfish-allergy-duotone-regular" {...props}></Icon>
<style>
:global(.g6hskxb9z) {
  fill: currentColor;
  d: path("M4 18a8 8 0 0 1 16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.myt_b32pc) {
  d: path("M4 18a8 8 0 0 1 16 0Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y29zmn0-m) {
  d: path("M5 20 19 6");
}

</style>
