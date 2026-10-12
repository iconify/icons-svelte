<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="x-88mqbcf"/><circle class="pk183qw0r"/><path class="ip1jjbrmk"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scooter" {...props}></Icon>
<style>
:global(.ip1jjbrmk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 19h.01");
}

:global(.pk183qw0r) {
  cx: 6.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pr2iyxt7r) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19h.01");
}

:global(.x-88mqbcf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.75v-1A5.75 5.75 0 0 1 8.75 10h2.75v6.75Zm8.5 0H15m2.6.04L15.5 5.25m-2.25 0h4.5");
}

:global(.xw30-oz_l) {
  cx: 18px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
