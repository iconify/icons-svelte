<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzsthfbrb"/><path class="yc_5gkigy"/><path class="vb4q6bcxh"/><path class="rvcsluzlj"/><path class="nzpsuduik"/><path class="tcxfk34nj"/><path class="ioilxfbca"/><path class="lcr-tiaxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sparsity-duotone-regular" {...props}></Icon>
<style>
:global(.ioilxfbca) {
  d: path("M14.5 6.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.lcr-tiaxf) {
  d: path("M9.5 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mzsthfbrb) {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.rvcsluzlj) {
  fill: currentColor;
  d: path("M9.5 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tcxfk34nj) {
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vb4q6bcxh) {
  fill: currentColor;
  d: path("M14.5 6.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yc_5gkigy) {
  fill: currentColor;
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
