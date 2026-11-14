<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_1nm19gp"/><path class="e_92r1bfh"/><path class="s7v73ac1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skin-cancer-check" {...props}></Icon>
<style>
:global(.e_92r1bfh) {
  fill: currentColor;
  d: path("M8.25 8c1.25-.75 2.75 0 3 1.5s-1 2.5-2.25 2.25s-2-1.5-1.5-2.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_1nm19gp) {
  d: path("M2.5 16.5c2.5-1 4.5 1 7 0c1.046-.392 1.955-.306 2.798-.17M7.5 5.5c2-1.5 5-.75 6 1.5s-.25 4 .25 5.75c.25 1.5-1.75 2.25-3.5 1.5c-2 .75-4.5 0-5-2s.75-3.5.5-4.75c0-.75.75-1.5 1.75-2");
}

:global(.s7v73ac1b) {
  d: path("m14.5 18l2.5 2.5l4.5-5");
}

</style>
