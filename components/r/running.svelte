<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dtnckfvpc"/><path class="aopv0ke_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:running" {...props}></Icon>
<style>
:global(.aopv0ke_q) {
  d: path("m19.25 9.5l-2.25 2L14 9l-3.75 1.25l-2.25 3");
}

:global(.dtnckfvpc) {
  d: path("M14 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M14 9l-2.25 5.5l4 2.5l-.75 4.5m-3.25-7L9 18.25l-4.25.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
