<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s1r9cubcf"/><path class="bhbaqd3_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:secret-rotation" {...props}></Icon>
<style>
:global(.bhbaqd3_h) {
  d: path("M7.25 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h5m-1.5 0v2.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1r9cubcf) {
  d: path("M5.5 15.75A7.5 7.5 0 0 1 12 4.5l-2-2m2 2l-2 2m8.5 1.75A7.5 7.5 0 0 1 12 19.5l2-2m-2 2l2 2");
}

</style>
