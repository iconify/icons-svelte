<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hj77z2ayq"/><path class="trfxszbrb"/><path class="j38utxbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:slow-down" {...props}></Icon>
<style>
:global(.hj77z2ayq) {
  d: path("M5 10.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j38utxbis) {
  d: path("M13 11a2.5 2.5 0 1 1-2.5-2.5");
}

:global(.trfxszbrb) {
  d: path("M2.5 16h15a2.5 2.5 0 0 0 2.5-2.5v-4m-1.25-3l1.25 3l1.5-2.75M3 19.5h18");
}

</style>
