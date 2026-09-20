<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgscl2bdj"/><path class="mypzt1bhf"/><path class="kgn0n6b1m"/><path class="d57k0dnmq"/><path class="ombslrhta"/><path class="dezc-zb_n"/><path class="zirb-hbnv"/><path class="n0hr0gbrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transport-duotone-regular" {...props}></Icon>
<style>
:global(.d57k0dnmq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16.5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dezc-zb_n) {
  d: path("M2 16.5h20");
}

:global(.kgn0n6b1m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 7.5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mypzt1bhf) {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0hr0gbrt) {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ombslrhta) {
  d: path("M2 7.5h20");
}

:global(.xgscl2bdj) {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zirb-hbnv) {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
