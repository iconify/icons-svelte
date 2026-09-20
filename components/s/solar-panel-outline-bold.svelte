<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s1r4963pp"/><path class="s09hy0b0y"/><path class="wcigoab1j"/><path class="m0f5ny81l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:solar-panel-outline-bold" {...props}></Icon>
<style>
:global(.m0f5ny81l) {
  d: path("M5 20h8");
}

:global(.s09hy0b0y) {
  d: path("M7 11h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s1r4963pp) {
  d: path("m4 14 6 -6h10l-6 6Z");
}

:global(.wcigoab1j) {
  d: path("M9 14v6");
}

</style>
