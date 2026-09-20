<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ky7fjq4zo"/><path class="n939_wb7j"/><path class="csyg-ybjs"/><path class="w4h0tcw_m"/><path class="tfnum6bjl"/><path class="z55just5o"/><path class="b4373m80b"/><path class="ryzx2-jfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subquestion-duotone-thin" {...props}></Icon>
<style>
:global(.b4373m80b) {
  d: path("M14.5 13.5A2.5 2.5 0 1 1 17 16");
}

:global(.csyg-ybjs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7a4 4 0 1 1 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ky7fjq4zo) {
  fill: currentColor;
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n939_wb7j) {
  fill: currentColor;
  d: path("M16 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ryzx2-jfe) {
  d: path("M16 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.tfnum6bjl) {
  d: path("M4 7a4 4 0 1 1 4 4");
}

:global(.w4h0tcw_m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 13.5A2.5 2.5 0 1 1 17 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z55just5o) {
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
