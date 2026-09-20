<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgrfb-bqu"/><path class="vjqs2ebif"/><path class="k6x6uv-ap"/><path class="s09hy0b0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:venue-outline-bold" {...props}></Icon>
<style>
:global(.k6x6uv-ap) {
  d: path("M12 11v8");
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

:global(.vjqs2ebif) {
  d: path("M5 6v13h14V6");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
