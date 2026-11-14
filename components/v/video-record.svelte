<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="izercdtxk"/><path class="j2uazj_zz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:video-record" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izercdtxk) {
  d: path("M6 6h6a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 12 18H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 6m9.5 4l6-3v10l-6-3");
}

:global(.j2uazj_zz) {
  fill: currentColor;
  d: path("M7 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
