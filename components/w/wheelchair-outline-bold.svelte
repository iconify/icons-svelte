<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m1v1ebb5g"/><path class="rynjb5q0q"/><path class="mtwnxab5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wheelchair-outline-bold" {...props}></Icon>
<style>
:global(.m1v1ebb5g) {
  d: path("M3 16a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.mtwnxab5w) {
  d: path("M8 3v6h7v4h4");
}

:global(.rynjb5q0q) {
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
