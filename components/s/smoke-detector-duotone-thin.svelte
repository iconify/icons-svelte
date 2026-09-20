<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m7cy9z-la"/><path class="bmz4u0b2r"/><path class="lqcp5xb1v"/><path class="tx4z1wb0w"/><path class="we3axlb2u"/><path class="zm2dyvb-o"/><path class="fmlaifbpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smoke-detector-duotone-thin" {...props}></Icon>
<style>
:global(.bmz4u0b2r) {
  fill: currentColor;
  d: path("M11 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fmlaifbpn) {
  d: path("M12 16v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lqcp5xb1v) {
  d: path("M4 3h16");
}

:global(.m7cy9z-la) {
  fill: currentColor;
  d: path("M5 6h14v5a7 7 0 0 1 -14 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tx4z1wb0w) {
  d: path("M5 6h14v5a7 7 0 0 1 -14 0Z");
}

:global(.we3axlb2u) {
  d: path("M11 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
