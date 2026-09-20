<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vu3nbmi6d"/><path class="sgdt4_0wi"/><path class="s09hy0b0y"/><path class="c6uw-ccfl"/><path class="kkid9bb2e"/><path class="spncj1b6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:surgery-duotone-regular" {...props}></Icon>
<style>
:global(.c6uw-ccfl) {
  d: path("M7 14h10");
}

:global(.kkid9bb2e) {
  d: path("M5 14a3 3 0 0 1 0 -6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s09hy0b0y) {
  d: path("M7 11h10");
}

:global(.sgdt4_0wi) {
  d: path("M5 8h14v5a7 5 0 0 1 -14 0Z");
}

:global(.spncj1b6w) {
  d: path("M19 8a3 3 0 0 1 0 6");
}

:global(.vu3nbmi6d) {
  fill: currentColor;
  d: path("M5 8h14v5a7 5 0 0 1 -14 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
