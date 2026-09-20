<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_2z93bzc"/><path class="yd2gt-b0a"/><path class="u8acqu0jc"/><path class="tcenmsthl"/><path class="uls5d7bvt"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:view-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k_2z93bzc) {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.tcenmsthl) {
  d: path("m3 12 6 -6h6l6 6");
}

:global(.u8acqu0jc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 12 6 6h6l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uls5d7bvt) {
  d: path("m3 12 6 6h6l6 -6");
}

:global(.yd2gt-b0a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 12 6 -6h6l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
