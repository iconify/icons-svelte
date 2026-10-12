<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="j9wbx_bng"/><path class="ial852b4e"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sightseeing-bus-sharp" {...props}></Icon>
<style>
:global(.hha4cxblz) {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ial852b4e) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.75h2.5V12H5Zm5.75 0h2.5V12h-2.5Zm5.75 0H19V12h-2.5Z");
}

:global(.j9wbx_bng) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5V5.25h12V7.5m-15.25 0h18.5v9.25H2.75z");
}

:global(.l0haxibzw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 19h.01");
}

:global(.ox2ue_b-w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

:global(.r_0b548wt) {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
