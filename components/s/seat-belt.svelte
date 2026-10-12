<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ckdeowbwc"/><path class="z706js3bw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:seat-belt" {...props}></Icon>
<style>
:global(.ckdeowbwc) {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z706js3bw) {
  d: path("M5 21.25h14a1 1 0 0 0 1-1v-1.5c0-4-3.6-6.5-8-6.5s-8 2.5-8 6.5v1.5a1 1 0 0 0 1 1m10-5.75l-4.75 3.25");
}

</style>
