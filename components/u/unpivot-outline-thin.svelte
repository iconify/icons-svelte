<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j4m0w2b-t"/><path class="p3dq04btg"/><path class="i9hpnuf0x"/><path class="z0ud8rb7a"/><path class="ys-dg812g"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unpivot-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9hpnuf0x) {
  d: path("M18 2v5.5");
}

:global(.j4m0w2b-t) {
  d: path("M6 2v5.5");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.p3dq04btg) {
  d: path("M12 2v5.5");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

:global(.z0ud8rb7a) {
  d: path("M9.5 10.5 12 13l2.5 -2.5");
}

</style>
