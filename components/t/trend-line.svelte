<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ux32n0bfz"/><circle class="oaykpkziz"/><circle class="r06hrywvu"/><circle class="na2sa9bxh"/><path class="h3oaqj1lq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trend-line" {...props}></Icon>
<style>
:global(.h3oaqj1lq) {
  d: path("M7.25 16.5L19.75 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.na2sa9bxh) {
  cx: 15px;
  cy: 5.5px;
  r: 1.5px;
}

:global(.oaykpkziz) {
  cx: 7.5px;
  cy: 11.75px;
  r: 1.5px;
}

:global(.r06hrywvu) {
  cx: 15.75px;
  cy: 13.75px;
  r: 1.5px;
}

:global(.ux32n0bfz) {
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5");
}

</style>
