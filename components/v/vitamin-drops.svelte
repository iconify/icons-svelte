<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tna36kpzr"/><path class="mdgmeouoz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vitamin-drops" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mdgmeouoz) {
  d: path("M9 15.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3-3v6m-2.5-4.5l5 3m-5 0l5-3");
}

:global(.tna36kpzr) {
  d: path("M10 10h4a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 18v-4.5A3.5 3.5 0 0 1 10 10m.5-2V5c0-2 3-2 3 0v3M9.75 8h4.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-4.5a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>
