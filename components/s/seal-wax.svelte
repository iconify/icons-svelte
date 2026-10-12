<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><path class="h5qqzbbnq"/><circle class="k0kijmlyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:seal-wax" {...props}></Icon>
<style>
:global(.h5qqzbbnq) {
  d: path("m2.75 6.75l6.7 3.85m11.8-3.85l-6.7 3.85");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k0kijmlyd) {
  cx: 12px;
  cy: 12.25px;
  r: 3px;
}

:global(.q0_gb6qzx) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

</style>
