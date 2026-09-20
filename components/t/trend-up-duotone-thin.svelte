<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-1kzjblr"/><path class="m9d8bbb2i"/><path class="q0ddccbcl"/><path class="kk-764bgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trend-up-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kk-764bgz) {
  d: path("M17 7h4v4");
}

:global(.m9d8bbb2i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 7h4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q0ddccbcl) {
  d: path("m3 17 6 -6 4 4 8 -8");
}

:global(.r-1kzjblr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 17 6 -6 4 4 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
