<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vktpe-yus"/><path class="i19gzxb0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tree-trunk" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i19gzxb0d) {
  d: path("M5 7v10.5l-2 3h18l-2-3V7M9 13v4m6-2.5v3");
}

:global(.vktpe-yus) {
  d: path("M5 7a7 3 0 1 0 14 0A7 3 0 1 0 5 7");
}

</style>
