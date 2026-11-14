<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdr0qjxed"/><path class="rtu8b9byv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wedding-rings" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rtu8b9byv) {
  d: path("M9 10.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.wdr0qjxed) {
  d: path("M3 13.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>
