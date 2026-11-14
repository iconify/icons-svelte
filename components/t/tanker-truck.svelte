<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkvxadb0n"/><path class="ihp6nfbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tanker-truck" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ihp6nfbah) {
  d: path("M15.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-13-4H16");
}

:global(.jkvxadb0n) {
  d: path("M2 10a7 4.5 0 1 0 14 0a7 4.5 0 1 0-14 0m14-2h3l2.5 4v4.5H16m-12 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
