<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="swquduh2r"/><path class="czikht1og"/><path class="uzf676bdq"/><path class="mb60vibde"/><path class="tljxsjbdo"/><path class="x0vbjnqyj"/><path class="b7nacdcee"/><path class="f8c172gmh"/><path class="qnmmmsbha"/><path class="zhf4ld96p"/><path class="tk_gkbbsy"/><path class="czv374byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shard-index-duotone-thin" {...props}></Icon>
<style>
:global(.b7nacdcee) {
  d: path("M3 6h6");
}

:global(.czikht1og) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.czv374byt) {
  d: path("M10 16h11");
}

:global(.f8c172gmh) {
  d: path("M12 6h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mb60vibde) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.swquduh2r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tk_gkbbsy) {
  d: path("M3 16h4");
}

:global(.tljxsjbdo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uzf676bdq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x0vbjnqyj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zhf4ld96p) {
  d: path("M17 11h4");
}

</style>
