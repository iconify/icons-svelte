<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixfqlr8_d"/><path class="bgtqag34q"/><path class="jc4egvb_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:solo-travel-outline-thin" {...props}></Icon>
<style>
:global(.bgtqag34q) {
  d: path("M2 21a8 8 0 0 1 16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixfqlr8_d) {
  d: path("M7 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.jc4egvb_a) {
  d: path("M16 9h4v7h-4Z");
}

</style>
