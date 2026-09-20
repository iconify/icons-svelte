<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lnxt6xb6t"/><path class="dxrv6e9dn"/><path class="n-7t0yb1r"/><path class="ecph9tq5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-quote-outline-regular" {...props}></Icon>
<style>
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
