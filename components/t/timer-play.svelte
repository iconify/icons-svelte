<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="fhcsjwttb"/><path class="pyf30w57g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:timer-play" {...props}></Icon>
<style>
:global(.fhcsjwttb) {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pyf30w57g) {
  d: path("M9.75 2.75h4.5m-2.25 0v3M17.5 8l1.75-1.75m-8.35 4.62l3.95 2.26q.65.37 0 .74l-3.95 2.26q-.65.37-.65-.38v-4.5q0-.75.65-.38");
}

</style>
