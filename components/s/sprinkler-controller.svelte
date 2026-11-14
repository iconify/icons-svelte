<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwjncbc1x"/><path class="og8la-bvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sprinkler-controller" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.og8la-bvv) {
  d: path("M7.25 7h3A1.75 1.75 0 0 1 12 8.75v2a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 7.25 7m8 2.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M7 16.5h.01m3.49 0h.01m3.49 0h.01");
}

:global(.pwjncbc1x) {
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 6 4");
}

</style>
