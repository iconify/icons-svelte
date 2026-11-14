<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z4h_u3ymx"/><path class="yhsozrbyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sandpit" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yhsozrbyk) {
  d: path("M5.5 16q3.25-2.5 6.5 0t6.5 0M15 2.5v6m-1.75-6h3.5m-3.5 6h3.5V11L15 12.75L13.25 11Z");
}

:global(.z4h_u3ymx) {
  d: path("M2.5 9.5V19a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2V9.5");
}

</style>
