<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nu0cj3v4x"/><path class="yvf-7bbca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:visibility-meter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nu0cj3v4x) {
  d: path("M10.223 14.985A7 7 0 0 1 9.75 15C6.6 15 4 13 2.5 9.75C4 6.5 6.6 4.5 9.75 4.5s5.75 2 7.25 5.25a11.3 11.3 0 0 1-1.175 1.998");
}

:global(.yvf-7bbca) {
  d: path("M7.25 9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M13 14.5h8.5M11 18h10.5M14 21.5h7");
}

</style>
