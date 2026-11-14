<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8d2p22ma"/><path class="ub6k34ain"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tare-scale" {...props}></Icon>
<style>
:global(.c8d2p22ma) {
  d: path("M5 7.5h14L20.5 21h-17Zm-.5-3h15m-7.5 0v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ub6k34ain) {
  d: path("M8 14.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4 0v-4");
}

</style>
