<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y_krt2u2w"/><path class="f967wobis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shrink-rate" {...props}></Icon>
<style>
:global(.f967wobis) {
  d: path("m3 7l9 4.5l4.5-2.25M12 11.5v10m6-16l1.5.75M21 8.5V10m-6.25 11.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y_krt2u2w) {
  d: path("M16.5 4.75L12 2.5L3 7v10l8.95 4.475M16.5 4.75v4.5l4.16 2.774");
}

</style>
