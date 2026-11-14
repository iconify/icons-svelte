<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is2rbwbhm"/><path class="ovcaeebyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scale-bar" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.is2rbwbhm) {
  d: path("M4 11h16a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 20 15H4a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 4 11M2.5 7v4M12 8v3m9.5-4v4");
}

:global(.ovcaeebyo) {
  fill: currentColor;
  d: path("M4 11h1.75a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 4 11m9.5 0h1.75a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5H13.5a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
