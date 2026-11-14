<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="lueip4s5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:workflow-file" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lueip4s5u) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M7.25 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m0 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M9 9.75v5.5M10.75 17h2.5");
}

:global(.w_a5jubhp) {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
