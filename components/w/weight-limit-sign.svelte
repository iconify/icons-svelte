<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="v4271ibcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:weight-limit-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.v4271ibcb) {
  d: path("M9.362 16h5.276a1.75 1.75 0 0 0 1.674-2.26l-.684-2.25a1.75 1.75 0 0 0-1.675-1.24h-3.906a1.75 1.75 0 0 0-1.675 1.24l-.684 2.25A1.75 1.75 0 0 0 9.362 16M10 7.5h4");
}

</style>
