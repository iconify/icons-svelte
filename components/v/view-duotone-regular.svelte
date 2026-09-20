<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k_2z93bzc"/><path class="qb_j1kiog"/><path class="encqelkvs"/><path class="tcenmsthl"/><path class="uls5d7bvt"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:view-duotone-regular" {...props}></Icon>
<style>
:global(.encqelkvs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 12 6 6h6l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qb_j1kiog) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 12 6 -6h6l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tcenmsthl) {
  d: path("m3 12 6 -6h6l6 6");
}

:global(.uls5d7bvt) {
  d: path("m3 12 6 6h6l6 -6");
}

</style>
