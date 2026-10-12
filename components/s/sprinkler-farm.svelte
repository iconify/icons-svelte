<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="sxsiyfbng"/><rect class="d03oe76xl"/><path class="m6mslobrx"/><path class="j9nijwbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sprinkler-farm" {...props}></Icon>
<style>
:global(.d03oe76xl) {
  width: 4px;
  height: 3px;
  x: 10px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.j9nijwbem) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 9.75h.01M5 9.75h.01m15.49 3h.01m-17.01 0h.01");
}

:global(.m6mslobrx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 10.25c1.75-2.5 4-4 7.25-4.25M10 10.25c-1.75-2.5-4-4-7.25-4.25");
}

:global(.sxsiyfbng) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.25h10m-5 0V12.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
