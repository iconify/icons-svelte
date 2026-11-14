<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rhiqs4b5r"/><path class="m75nhibta"/><path class="owi6a9bzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:turf-roll" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m75nhibta) {
  d: path("M7 6.5h10.5a4 6.5 0 0 1 0 13H7");
}

:global(.owi6a9bzg) {
  d: path("M7 16a2 3 0 1 1 2-3m2-6.5l-.75-2.75M14.5 6.5l-.75-2.75M18 6.5L17.5 4");
}

:global(.rhiqs4b5r) {
  d: path("M3 13a4 6.5 0 1 0 8 0a4 6.5 0 1 0-8 0");
}

</style>
