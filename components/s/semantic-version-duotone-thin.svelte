<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwys7tb-b"/><path class="c5icmybsm"/><path class="avartybbb"/><path class="gvu3jzbph"/><path class="phup74asp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:semantic-version-duotone-thin" {...props}></Icon>
<style>
:global(.avartybbb) {
  d: path("M11 9.5v5");
}

:global(.c5icmybsm) {
  d: path("m4 12 6 -6h10v12H10Z");
}

:global(.gvu3jzbph) {
  d: path("M14 9.5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwys7tb-b) {
  fill: currentColor;
  d: path("m4 12 6 -6h10v12H10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.phup74asp) {
  d: path("M17 9.5v5");
}

</style>
