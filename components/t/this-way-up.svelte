<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pxs7obchh"/><path class="nthnoib9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:this-way-up" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nthnoib9k) {
  d: path("m9 11l3-3l3 3");
}

:global(.pxs7obchh) {
  d: path("M8.5 4.5h7A3.5 3.5 0 0 1 19 8v8a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 16V8a3.5 3.5 0 0 1 3.5-3.5M12 8v8");
}

</style>
