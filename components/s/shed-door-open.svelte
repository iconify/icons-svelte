<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgqtned1z"/><path class="j25afqu4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shed-door-open" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j25afqu4l) {
  d: path("M6 21V11h9v10m0-10l3.25 1.5v7L15 21m-4.5-7.25v4.5m-1.75 0h3.5");
}

:global(.xgqtned1z) {
  d: path("m3.676 9.475l7.25-5.639a1.75 1.75 0 0 1 2.148 0l7.25 5.639A1.75 1.75 0 0 1 21 10.856v8.394A1.75 1.75 0 0 1 19.25 21H4.75A1.75 1.75 0 0 1 3 19.25v-8.394a1.75 1.75 0 0 1 .676-1.381");
}

</style>
