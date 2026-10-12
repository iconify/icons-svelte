<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eqgjd28gw"/><circle class="qi0czrdcc"/><path class="kvsxdhb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stress" {...props}></Icon>
<style>
:global(.eqgjd28gw) {
  d: path("M4.75 5.5L7.17 3l2.41 2.5L12 3l2.42 2.5L16.83 3l2.42 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kvsxdhb9c) {
  d: path("M5 21.25h14a1 1 0 0 0 1-1c0-2.6-3.6-4.5-8-4.5s-8 1.9-8 4.5a1 1 0 0 0 1 1");
}

:global(.qi0czrdcc) {
  cx: 12px;
  cy: 10.5px;
  r: 3px;
}

</style>
