<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw8buxbld"/><path class="dmrkpqeas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skater-glide" {...props}></Icon>
<style>
:global(.dmrkpqeas) {
  d: path("M11 21h6a1.5 1.5 0 0 0 1.5-1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iw8buxbld) {
  d: path("M11.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2 5.25L13 14.5m-5-2l10.5-3M5 16.5l8-2l1 6.5");
}

</style>
