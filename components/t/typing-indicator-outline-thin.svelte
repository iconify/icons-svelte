<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_k8-6b4x"/><path class="ebuv7_btt"/><path class="g-g6w6buq"/><path class="drftkjb-q"/><path class="me7c_bbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:typing-indicator-outline-thin" {...props}></Icon>
<style>
:global(.b_k8-6b4x) {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.drftkjb-q) {
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ebuv7_btt) {
  d: path("M7 17v3l3 -3");
}

:global(.g-g6w6buq) {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.me7c_bbry) {
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
