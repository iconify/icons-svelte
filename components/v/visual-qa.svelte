<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ney67qiwg"/><path class="k2oelr3kv"/><path class="j_2pr43cx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:visual-qa" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_2pr43cx) {
  d: path("M15 14.5a1.25 1.25 0 1 1 1.75 1.15v.6");
}

:global(.k2oelr3kv) {
  d: path("m5.5 11l3-3l2.5 2.5m2.25.75h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-3.5l-2.5 2v-2a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2");
}

:global(.ney67qiwg) {
  width: 13.5px;
  height: 11px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.25px;
}

</style>
