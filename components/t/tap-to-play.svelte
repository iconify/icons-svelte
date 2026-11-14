<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_-si6l4d"/><path class="vwuid0-nz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tap-to-play" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_-si6l4d) {
  d: path("m8.497 4.95l7.851 4.812a2.625 2.625 0 0 1 0 4.476L8.497 19.05A2.625 2.625 0 0 1 4.5 16.812V7.188A2.625 2.625 0 0 1 8.497 4.95");
}

:global(.vwuid0-nz) {
  d: path("M8 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
