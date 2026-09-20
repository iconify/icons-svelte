<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p8iop6bwz"/><path class="ny5wseb0c"/><path class="h0f754b1g"/><path class="ikqld8lly"/><path class="q6rh9u55e"/><path class="v_a3lnirg"/><path class="lvtw3tv7j"/><path class="c-xj8zban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ski-run-duotone-bold" {...props}></Icon>
<style>
:global(.c-xj8zban) {
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h0f754b1g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21 18 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ikqld8lly) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 21 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lvtw3tv7j) {
  d: path("m16 21 5 -5");
}

:global(.ny5wseb0c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18 15 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8iop6bwz) {
  fill: currentColor;
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q6rh9u55e) {
  d: path("M3 18 15 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v_a3lnirg) {
  d: path("M6 21 18 9");
}

</style>
