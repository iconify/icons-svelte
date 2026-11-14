<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u18_l1bej"/><path class="bgotw-ofq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:year-end-tax-statement" {...props}></Icon>
<style>
:global(.bgotw-ofq) {
  d: path("M8 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-4 .5l6-7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u18_l1bej) {
  d: path("M5 2.5h14v19L17 20l-2 1.5l-2-1.5l-2 1.5L9 20l-2 1.5L5 20Z");
}

</style>
