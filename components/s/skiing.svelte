<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ywh8odbvx"/><path class="r4nh24c8a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:skiing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r4nh24c8a) {
  d: path("m9.5 7.75l2 5L14 15l-1.75 3.4M10 9.25l3.75.5L16 12m-.75-1.5L17 17M3.75 15.5L20 21");
}

:global(.ywh8odbvx) {
  cx: 8.25px;
  cy: 5px;
  r: 2px;
}

</style>
