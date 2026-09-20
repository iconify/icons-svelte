<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oa34-acln"/><path class="hc491gbyo"/><path class="x6_f3nb7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:storage-box-outline-thin" {...props}></Icon>
<style>
:global(.hc491gbyo) {
  d: path("M5 10v10h14V10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oa34-acln) {
  d: path("M3 6v4h18V6Z");
}

:global(.x6_f3nb7s) {
  d: path("M10 14h4v3h-4Z");
}

</style>
