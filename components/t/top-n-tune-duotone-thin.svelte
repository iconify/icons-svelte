<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ge4agrbum"/><path class="x7tx8ri1m"/><path class="dno8iacks"/><path class="ww4s5kyfz"/><path class="mnsqkpw4z"/><path class="zrmtxyafv"/><path class="u07qp3bhr"/><path class="kiz2lrbtx"/><path class="y_or9-s0p"/><path class="yqy8x4bvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-n-tune-duotone-thin" {...props}></Icon>
<style>
:global(.dno8iacks) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ge4agrbum) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kiz2lrbtx) {
  d: path("M8 14h12");
}

:global(.mnsqkpw4z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 2H3v9h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u07qp3bhr) {
  d: path("M8 9h12");
}

:global(.ww4s5kyfz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7tx8ri1m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y_or9-s0p) {
  d: path("M8 19h12");
}

:global(.yqy8x4bvc) {
  d: path("M5.5 2H3v9h2.5");
}

:global(.zrmtxyafv) {
  d: path("M8 4h12");
}

</style>
