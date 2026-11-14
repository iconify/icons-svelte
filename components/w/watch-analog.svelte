<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j51f-ebgg"/><path class="nannkfw4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:watch-analog" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j51f-ebgg) {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.nannkfw4h) {
  d: path("M8.5 7.25L9 3h6l.5 4.25m-7 9.5L9 21h6l.5-4.25M12 9.5V12l1.75 1");
}

</style>
