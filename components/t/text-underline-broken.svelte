<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="poyc1firz"/><path class="cyqsccb0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-underline-broken" {...props}></Icon>
<style>
:global(.cyqsccb0j) {
  d: path("M4 3V9C4 11.5264 5.17108 13.7792 7 15.2454M20 3V9C20 13.4183 16.4183 17 12 17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.poyc1firz) {
  d: path("M4 21H20");
}

</style>
