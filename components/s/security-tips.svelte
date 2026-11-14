<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xo6vk9i6m"/><path class="bb5hijb1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:security-tips" {...props}></Icon>
<style>
:global(.bb5hijb1a) {
  d: path("m9.75 10l1.75 1.75l3-3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xo6vk9i6m) {
  d: path("M9 17v-1.5c-2-1.3-3-3.3-3-5.5a6 6 0 0 1 12 0c0 2.2-1 4.2-3 5.5V17Zm.5 2.5h5m-4 2h3");
}

</style>
