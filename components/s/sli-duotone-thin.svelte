<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0f0f2w0j"/><path class="jatp6jb0f"/><path class="gqnrk6bxj"/><path class="jfhg8zbol"/><path class="aig5gcc6s"/><path class="me177l4bh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sli-duotone-thin" {...props}></Icon>
<style>
:global(.a0f0f2w0j) {
  fill: currentColor;
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.aig5gcc6s) {
  d: path("m12 17 5 -5");
}

:global(.gqnrk6bxj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 17 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jatp6jb0f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jfhg8zbol) {
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
}

:global(.me177l4bh) {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
