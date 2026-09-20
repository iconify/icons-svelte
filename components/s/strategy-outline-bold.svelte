<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aeyekmbly"/><path class="axr3xwb0d"/><path class="cn1mb64lb"/><path class="r1wy_ibgj"/><path class="jhhozmbca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:strategy-outline-bold" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.axr3xwb0d) {
  d: path("m7 17 4 -4");
}

:global(.cn1mb64lb) {
  d: path("M11 13h4");
}

:global(.jhhozmbca) {
  d: path("M19 5v4h-4");
}

:global(.r1wy_ibgj) {
  d: path("m15 13 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
