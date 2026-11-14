<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qilcokbmh"/><path class="m7oi74iev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wifi-zone-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m7oi74iev) {
  d: path("M9.75 9.5a3 3 0 0 1 4.5 0m-6.5-2.25a6 6 0 0 1 8.5 0");
}

:global(.qilcokbmh) {
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v5a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 11V6A3.5 3.5 0 0 1 7 2.5m5 12v7m0-10h.01");
}

</style>
