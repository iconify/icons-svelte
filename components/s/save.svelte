<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="osk55nmlo"/><path class="zdutghbid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:save" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.osk55nmlo) {
  d: path("M7.5 4h7.55a3.5 3.5 0 0 1 2.475 1.025l1.45 1.45A3.5 3.5 0 0 1 20 8.95v7.55a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 16.5v-9A3.5 3.5 0 0 1 7.5 4");
}

:global(.zdutghbid) {
  d: path("M7.5 20v-5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v5M8 4v3a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V4");
}

</style>
