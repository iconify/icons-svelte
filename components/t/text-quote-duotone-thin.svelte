<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i05jgw93o"/><path class="ymi5ubiwk"/><path class="wtr271uqu"/><path class="o6a3qip5v"/><path class="lnxt6xb6t"/><path class="dxrv6e9dn"/><path class="n-7t0yb1r"/><path class="ecph9tq5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-quote-duotone-thin" {...props}></Icon>
<style>
:global(.dxrv6e9dn) {
  d: path("M7 5v3h2.5");
}

:global(.ecph9tq5i) {
  d: path("M3 18h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i05jgw93o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5v3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lnxt6xb6t) {
  d: path("M3 5v3h2.5");
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.o6a3qip5v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wtr271uqu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymi5ubiwk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
