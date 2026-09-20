<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="phm20ubpt"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="hdrgscbgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trend-milestone-duotone-thin" {...props}></Icon>
<style>
:global(.bnrf8ghpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.hdrgscbgb) {
  d: path("m9 13 2 -2 2 2 2 -2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.phm20ubpt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 13 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
