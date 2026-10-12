<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qnq0mhbyd"/><circle class="g8q59cbpc"/><path class="f__gbmrya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sku-label" {...props}></Icon>
<style>
:global(.f__gbmrya) {
  d: path("M11.5 9.25v5.5m2.5-5.5v5.5m2.5-5.5v5.5");
}

:global(.g8q59cbpc) {
  cx: 7.5px;
  cy: 12px;
  r: 1.1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qnq0mhbyd) {
  d: path("M8.66 5.75h10.59a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2H8.66a2 2 0 0 1-1.48-.66l-3.86-4.25a2 2 0 0 1 0-2.68l3.86-4.25a2 2 0 0 1 1.48-.66");
}

</style>
