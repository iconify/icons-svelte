<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xm7c2-bof"/><path class="k6n_hdb4q"/><path class="xddmfbgnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:set-top-box" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6n_hdb4q) {
  fill: currentColor;
  d: path("M6.5 11h.01");
}

:global(.xddmfbgnf) {
  d: path("M10 11h8");
}

:global(.xm7c2-bof) {
  d: path("M6 6.5h12a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 12v-2A3.5 3.5 0 0 1 6 6.5m-.5 9V18m13-2.5V18");
}

</style>
