<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vn6-6774p"/><path class="s1r4963pp"/><path class="s09hy0b0y"/><path class="wcigoab1j"/><path class="m0f5ny81l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:solar-panel-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0f5ny81l) {
  d: path("M5 20h8");
}

:global(.s09hy0b0y) {
  d: path("M7 11h10");
}

:global(.s1r4963pp) {
  d: path("m4 14 6 -6h10l-6 6Z");
}

:global(.vn6-6774p) {
  fill: currentColor;
  d: path("m4 14 6 -6h10l-6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wcigoab1j) {
  d: path("M9 14v6");
}

</style>
