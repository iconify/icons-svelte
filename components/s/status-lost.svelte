<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqpssobwz"/><path class="fqostxb6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:status-lost" {...props}></Icon>
<style>
:global(.fqostxb6q) {
  d: path("M10 12.25a2 2 0 1 1 3.5 1.5l-1.5 1v.5m0 3.25h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tqpssobwz) {
  d: path("M4.75 3h14.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25H4.75A2.25 2.25 0 0 1 2.5 5.25A2.25 2.25 0 0 1 4.75 3m1.875 4.5h10.75A2.625 2.625 0 0 1 20 10.125v8.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-8.75A2.625 2.625 0 0 1 6.625 7.5");
}

</style>
