<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sw_hwrbxs"/><path class="jzeve79sx"/><path class="dpd39d9rw"/><path class="d-_x6ccub"/><path class="gghaaub-j"/><path class="knb00ei4h"/><path class="ymw3aibdo"/><path class="awxqv1b4c"/><path class="dgfbh6b4z"/><path class="ji1cfccfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sampling-duotone-bold" {...props}></Icon>
<style>
:global(.awxqv1b4c) {
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.d-_x6ccub) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dgfbh6b4z) {
  d: path("M12 9v9");
}

:global(.dpd39d9rw) {
  fill: currentColor;
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gghaaub-j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 15 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ji1cfccfb) {
  d: path("m9 15 3 3 3 -3");
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.knb00ei4h) {
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sw_hwrbxs) {
  fill: currentColor;
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
