<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9jjrhblk"/><path class="i1qxrtbqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:warm-up-stretch" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1qxrtbqn) {
  d: path("m4 8l8 2.5L20 8");
}

:global(.v9jjrhblk) {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 4V14l-5 7m5-7l5 7");
}

</style>
