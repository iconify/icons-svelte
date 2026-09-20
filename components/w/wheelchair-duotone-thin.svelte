<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ndzpn0bnu"/><path class="xlm4t5bbx"/><path class="m1v1ebb5g"/><path class="rynjb5q0q"/><path class="mtwnxab5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wheelchair-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m1v1ebb5g) {
  d: path("M3 16a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.mtwnxab5w) {
  d: path("M8 3v6h7v4h4");
}

:global(.ndzpn0bnu) {
  fill: currentColor;
  d: path("M3 16a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rynjb5q0q) {
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xlm4t5bbx) {
  fill: currentColor;
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
