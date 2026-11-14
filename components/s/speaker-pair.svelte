<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="owyfjfnrk"/><path class="rixh-tb0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:speaker-pair" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.owyfjfnrk) {
  d: path("M6 4h1a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 7 20H6a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 6 4m11 0h1a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 18 20h-1a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 17 4");
}

:global(.rixh-tb0x) {
  d: path("M4.5 14.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-6h.01m8.99 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-6h.01");
}

</style>
