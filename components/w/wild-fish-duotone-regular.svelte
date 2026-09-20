<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h-g3lgb-r"/><path class="guoi_acnp"/><path class="gt1864neo"/><path class="m68-9jb2y"/><path class="g-g6w6buq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wild-fish-duotone-regular" {...props}></Icon>
<style>
:global(.g-g6w6buq) {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gt1864neo) {
  d: path("M4 13a8 5 0 0 1 14 0 8 5 0 0 1 -14 0");
}

:global(.guoi_acnp) {
  fill: currentColor;
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h-g3lgb-r) {
  fill: currentColor;
  d: path("M4 13a8 5 0 0 1 14 0 8 5 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m68-9jb2y) {
  d: path("m17 9 4 4 -4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
