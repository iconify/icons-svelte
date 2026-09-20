<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c-iufdcsb"/><path class="navc76bal"/><path class="gnn1wob3e"/><path class="umugi_b9i"/><path class="fmlaifbpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:switch-case-duotone-thin" {...props}></Icon>
<style>
:global(.c-iufdcsb) {
  fill: currentColor;
  d: path("m12 4 6 6 -6 6 -6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fmlaifbpn) {
  d: path("M12 16v4");
}

:global(.gnn1wob3e) {
  d: path("M18 10h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.navc76bal) {
  d: path("m12 4 6 6 -6 6 -6 -6Z");
}

:global(.umugi_b9i) {
  d: path("M3 10h3");
}

</style>
