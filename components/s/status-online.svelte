<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0d0y_bae"/><path class="nkl72kbds"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:status-online" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nkl72kbds) {
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

:global(.t0d0y_bae) {
  fill: currentColor;
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
