<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hqs3z7wnn"/><path class="knhft4qdm"/><path class="wgtcdk8rf"/><path class="hxpdvgpky"/><path class="zitd6_pbm"/><path class="eljxzwbgp"/><path class="k4qo1xe9v"/><path class="rjl8fe1sw"/><path class="ed-cudrmv"/><path class="i7797vbcv"/><path class="gzw9grb_d"/><path class="c4khiwgvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-playground-duotone-regular" {...props}></Icon>
<style>
:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.ed-cudrmv) {
  d: path("M20 6v14");
}

:global(.eljxzwbgp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gzw9grb_d) {
  d: path("M15 6v9");
}

:global(.hqs3z7wnn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hxpdvgpky) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 6v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i7797vbcv) {
  d: path("M9 6v9");
}

:global(.k4qo1xe9v) {
  d: path("M4 6h16");
}

:global(.knhft4qdm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rjl8fe1sw) {
  d: path("M4 6v14");
}

:global(.wgtcdk8rf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zitd6_pbm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 6v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
