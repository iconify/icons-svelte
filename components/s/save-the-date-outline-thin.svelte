<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ll9y16bbt"/><path class="jof7c9fpk"/><path class="d27-dpb3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:save-the-date-outline-thin" {...props}></Icon>
<style>
:global(.d27-dpb3f) {
  d: path("M9 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jof7c9fpk) {
  d: path("M4 9h16");
}

:global(.ll9y16bbt) {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v13a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
