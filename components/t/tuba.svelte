<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uccl4misb"/><path class="odq0kwbtm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tuba" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.odq0kwbtm) {
  d: path("M6 15.75a6 5.25 0 1 0 12 0a6 5.25 0 1 0-12 0m1.76-3.71L4.5 9.5M9 13.25v4m3-4v4m3-4v4");
}

:global(.uccl4misb) {
  d: path("M6.75 3.5q0-.75.75-.75h9q.75 0 .75.75c-.25 2.5-2.5 4.25-4 5v2h-2.5v-2c-1.5-.75-3.75-2.5-4-5");
}

</style>
