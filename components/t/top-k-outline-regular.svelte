<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="r4xjkv11f"/><path class="n-7t0yb1r"/><path class="ukjt4fb6s"/><path class="yvi-t83_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-k-outline-regular" {...props}></Icon>
<style>
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

:global(.r4xjkv11f) {
  d: path("M3 10h15");
}

:global(.ukjt4fb6s) {
  d: path("M3 17h12");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.yvi-t83_e) {
  d: path("M3 21h9");
}

</style>
