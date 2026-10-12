<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jl4903ezj"/><path class="mrdleacin"/><rect class="dqnyj2bne"/><path class="cgrv-9bol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ssl-certificate" {...props}></Icon>
<style>
:global(.cgrv-9bol) {
  d: path("M10.5 8.5V7a1.5 1.5 0 0 1 3 0v1.5");
}

:global(.dqnyj2bne) {
  width: 5px;
  height: 4px;
  x: 9.5px;
  y: 8.5px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jl4903ezj) {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

:global(.mrdleacin) {
  d: path("m8.5 14.73l-1.25 6.52l4.75-2.5l4.75 2.5l-1.25-6.52");
}

</style>
