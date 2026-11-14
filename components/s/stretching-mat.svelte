<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f1a5tcbce"/><path class="ybbk-rriu"/><path class="f6-gvibuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stretching-mat" {...props}></Icon>
<style>
:global(.f1a5tcbce) {
  d: path("M4.25 10.5L15.75 5a4 4 0 0 1 3.5 7l-11.5 5.5");
}

:global(.f6-gvibuw) {
  d: path("M6 12.75A1.25 1.25 0 1 1 4.75 14m6-6.5l3.5 7m-1-8.25l3.5 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybbk-rriu) {
  d: path("M2 14a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
