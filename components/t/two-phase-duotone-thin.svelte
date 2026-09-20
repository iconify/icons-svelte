<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzin226yh"/><path class="ja4e6ac_k"/><path class="yjik3t7vc"/><path class="h9i3bw3au"/><path class="n6_f133dv"/><path class="upuk2bbmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:two-phase-duotone-thin" {...props}></Icon>
<style>
:global(.h9i3bw3au) {
  d: path("m5 8 2 2 3.5 -3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja4e6ac_k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 16 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n6_f133dv) {
  d: path("m5 16 2 2 3.5 -3.5");
}

:global(.upuk2bbmi) {
  d: path("M15.5 5H18v14h-2.5");
}

:global(.xzin226yh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 8 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yjik3t7vc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 5H18v14h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
