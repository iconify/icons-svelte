<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="u40y9sb5p"/><path class="gkixhdctr"/><path class="czlqulb3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:slideshow" {...props}></Icon>
<style>
:global(.czlqulb3m) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 7.75h.01M8.25 20.5h.01m7.49 0h.01m-4.76 0h2");
}

:global(.gkixhdctr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 14.25L10 10.5l2.5 2.75l1.75-1.75l3.25 2.75");
}

:global(.u40y9sb5p) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
