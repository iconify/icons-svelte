<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s0k4vjb0g"/><path class="k9pwki3xr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:waypoint" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k9pwki3xr) {
  d: path("M13.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M7 19h6q2.5 0 2.5-2.5");
}

:global(.s0k4vjb0g) {
  d: path("M15.5 16.5s-5.5-5-5.5-8a5.5 5.5 0 0 1 11 0c0 3-5.5 8-5.5 8M3 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
