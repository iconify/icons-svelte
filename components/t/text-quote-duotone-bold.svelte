<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w7d8ui3is"/><path class="rvse0kbol"/><path class="wsc8jcb1j"/><path class="a97ht-z9f"/><path class="lnxt6xb6t"/><path class="dxrv6e9dn"/><path class="n-7t0yb1r"/><path class="ecph9tq5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-quote-duotone-bold" {...props}></Icon>
<style>
:global(.a97ht-z9f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dxrv6e9dn) {
  d: path("M7 5v3h2.5");
}

:global(.ecph9tq5i) {
  d: path("M3 18h12");
}

:global(.lnxt6xb6t) {
  d: path("M3 5v3h2.5");
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.rvse0kbol) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 5v3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w7d8ui3is) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5v3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wsc8jcb1j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
