<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovv0shrzd"/><path class="ijm8161nx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:singleton" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ijm8161nx) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.ovv0shrzd) {
  d: path("M14.907 4.013a8.5 8.5 0 0 1 5.08 5.08m0 5.814a8.5 8.5 0 0 1-5.08 5.08m-5.814 0a8.5 8.5 0 0 1-5.08-5.08m0-5.814a8.5 8.5 0 0 1 5.08-5.08");
}

</style>
