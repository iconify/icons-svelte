<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k5mfw8-4w"/><path class="nnvzb1aji"/><path class="iwa0k9ghp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:work-from-home" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwa0k9ghp) {
  d: path("M10 13h4a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 14 17h-4a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 10 13m-2.5 7.5h9");
}

:global(.k5mfw8-4w) {
  d: path("M3.5 11.5L12 4l8.5 7.5");
}

:global(.nnvzb1aji) {
  d: path("M5.5 10v10.5h13V10");
}

</style>
