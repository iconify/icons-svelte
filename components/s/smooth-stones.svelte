<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tfsrfuvdq"/><path class="q0mz0bimm"/><path class="mhobl8e_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smooth-stones" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mhobl8e_v) {
  d: path("M8.5 5.75a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0");
}

:global(.q0mz0bimm) {
  d: path("M10.5 7.5a6 3 0 1 0 3 0");
}

:global(.tfsrfuvdq) {
  d: path("M15 13a8.5 3.5 0 1 1-6 0");
}

</style>
