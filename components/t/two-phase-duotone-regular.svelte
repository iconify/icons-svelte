<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v75_tmb0p"/><path class="jtpx599hr"/><path class="cg4i0cc0y"/><path class="h9i3bw3au"/><path class="n6_f133dv"/><path class="upuk2bbmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:two-phase-duotone-regular" {...props}></Icon>
<style>
:global(.cg4i0cc0y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.5 5H18v14h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h9i3bw3au) {
  d: path("m5 8 2 2 3.5 -3.5");
}

:global(.jtpx599hr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 16 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n6_f133dv) {
  d: path("m5 16 2 2 3.5 -3.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.upuk2bbmi) {
  d: path("M15.5 5H18v14h-2.5");
}

:global(.v75_tmb0p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 8 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
