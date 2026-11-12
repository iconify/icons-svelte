<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i6spdsbgb"/><path class="rm9mgg4hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-horizontal-broken" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6spdsbgb) {
  d: path("M10.125 12L6 8L10.125 4M6 8L13 8M18 8H16");
}

:global(.rm9mgg4hf) {
  d: path("M13.875 20L18 16L13.875 12M18 16L11 16M6 16H8");
}

</style>
