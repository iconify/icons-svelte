<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dirwcibkh"/><path class="ah8jctbmd"/><circle class="k6r3zgz2g"/><circle class="sotefpb_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toy-train" {...props}></Icon>
<style>
:global(.ah8jctbmd) {
  d: path("M15 7.5h3.25v3.75H15Z");
}

:global(.dirwcibkh) {
  d: path("M2.75 13.25V10q0-1 1-1t1-1V5.5q0-1 1-1h1.5q1 0 1 1V8q0 1 1 1H11q1 0 1-1V5.5q0-1 1-1h7.25q1 0 1 1v7.75q0 1-1 1H3.75q-1 0-1-1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6r3zgz2g) {
  cx: 6.75px;
  cy: 19.25px;
  r: 2px;
}

:global(.sotefpb_j) {
  cx: 17px;
  cy: 19.25px;
  r: 2px;
}

</style>
