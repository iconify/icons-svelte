<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="z13ah3brv"/><path class="kx3_wwbww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:walk-green" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kx3_wwbww) {
  d: path("M12.5 8L11 13.5l2.75 3l.5 4.75M11 13.5l-2.5 7.25M12.25 9L9 11.5M12.25 9L15 11.25m1.5 10c0-3 1.75-4.75 4.75-5.25c0 3-1.75 4.75-4.75 5.25");
}

:global(.z13ah3brv) {
  cx: 13px;
  cy: 4.5px;
  r: 1.75px;
}

</style>
