<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kc7n1fbzv"/><path class="yxvppjbfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:workflow-cache" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kc7n1fbzv) {
  d: path("M5.125 11.5h1.25A2.625 2.625 0 0 1 9 14.125v1.25A2.625 2.625 0 0 1 6.375 18h-1.25A2.625 2.625 0 0 1 2.5 15.375v-1.25A2.625 2.625 0 0 1 5.125 11.5m10.5-9h1.25A2.625 2.625 0 0 1 19.5 5.125v1.25A2.625 2.625 0 0 1 16.875 9h-1.25A2.625 2.625 0 0 1 13 6.375v-1.25A2.625 2.625 0 0 1 15.625 2.5m-9.875 9V5.75H13m2 10a3.25 1.5 0 1 0 6.5 0a3.25 1.5 0 1 0-6.5 0");
}

:global(.yxvppjbfk) {
  d: path("M15 15.75V20a3.25 1.5 0 0 0 6.5 0v-4.25");
}

</style>
