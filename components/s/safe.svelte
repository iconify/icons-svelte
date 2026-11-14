<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hky1aeb5i"/><path class="dj_kijbmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:safe" {...props}></Icon>
<style>
:global(.dj_kijbmi) {
  d: path("M7.5 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m10-2v4");
}

:global(.hky1aeb5i) {
  d: path("M6.5 3.5h11A3.5 3.5 0 0 1 21 7v9a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 16V7a3.5 3.5 0 0 1 3.5-3.5m0 16V21m11-1.5V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
