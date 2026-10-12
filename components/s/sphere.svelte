<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hwsal5q-o"/><path class="ws3khsbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sphere" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwsal5q-o) {
  cx: 12px;
  cy: 12px;
  r: 8px;
}

:global(.ws3khsbra) {
  d: path("M6.83 10.12a5.5 5.5 0 0 1 3.29-3.29");
}

</style>
