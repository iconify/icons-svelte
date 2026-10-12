<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="gx4ah_6qi"/><path class="xmxyydbzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stretching" {...props}></Icon>
<style>
:global(.gx4ah_6qi) {
  cx: 16px;
  cy: 5px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xmxyydbzr) {
  d: path("m12 13.5l-4.5 7.75M12 13.5l4.5 7.75M12 13.5l1.75-5.75m-.25.75c-1.5-3.25-4-4.5-7-4m7 4l3 4");
}

</style>
