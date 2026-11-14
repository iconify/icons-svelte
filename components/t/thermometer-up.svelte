<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsskzewvy"/><path class="wdbnirxoe"/><path class="qawz0cb-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermometer-up" {...props}></Icon>
<style>
:global(.bsskzewvy) {
  d: path("M4.25 12.5v-7a3 3 0 0 1 6 0v7a5 5 0 1 1-6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qawz0cb-i) {
  d: path("M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

:global(.wdbnirxoe) {
  fill: currentColor;
  d: path("M5.25 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
