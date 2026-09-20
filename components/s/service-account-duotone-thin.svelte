<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_0ghfb0y"/><path class="mzv5l34he"/><path class="yxnzj4kct"/><path class="wlnjwfbkn"/><path class="jtqt-jkjg"/><path class="ptxh1kbpm"/><path class="avdamgajo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:service-account-duotone-thin" {...props}></Icon>
<style>
:global(.avdamgajo) {
  d: path("M6 21a6 6 0 0 1 12 0");
}

:global(.b_0ghfb0y) {
  fill: currentColor;
  d: path("M7 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jtqt-jkjg) {
  d: path("M9 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mzv5l34he) {
  fill: currentColor;
  d: path("M9 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ptxh1kbpm) {
  d: path("M13 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wlnjwfbkn) {
  d: path("M7 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

:global(.yxnzj4kct) {
  fill: currentColor;
  d: path("M13 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
