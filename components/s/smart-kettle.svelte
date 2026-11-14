<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtz-edbbx"/><path class="ueg9qzsbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smart-kettle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jtz-edbbx) {
  d: path("M11.372 16H2.5v-3.5c0-3 2.25-5 4.75-5s4.75 2 4.75 5v2.528");
}

:global(.ueg9qzsbc) {
  d: path("M3 10.5C2 1 11.25.5 11.25 10m.75 3l4.5-4.5m-14 10.25H11M14 17a5.66 5.66 0 0 1 8 0m-6 2a2.83 2.83 0 0 1 4 0m-2 2h.01");
}

</style>
