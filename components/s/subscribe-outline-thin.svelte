<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7phtvv5f"/><path class="p-74fg5cj"/><path class="vz5_16nyg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subscribe-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7phtvv5f) {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p-74fg5cj) {
  d: path("M5 12a7 7 0 0 1 7 7");
}

:global(.vz5_16nyg) {
  d: path("M5 6a13 13 0 0 1 13 13");
}

</style>
