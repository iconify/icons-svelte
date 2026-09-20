<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xiota8z6p"/><path class="x7aiqk4zc"/><path class="jlpxneb5g"/><path class="wg8_ddc1f"/><path class="e0fatccfd"/><path class="wn519caci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spend-duotone-thin" {...props}></Icon>
<style>
:global(.e0fatccfd) {
  d: path("M18 12h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlpxneb5g) {
  d: path("M9 8v8");
}

:global(.wg8_ddc1f) {
  d: path("M6 12h6");
}

:global(.wn519caci) {
  d: path("m19 9 3 3 -3 3");
}

:global(.x7aiqk4zc) {
  d: path("M2 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.xiota8z6p) {
  fill: currentColor;
  d: path("M2 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
