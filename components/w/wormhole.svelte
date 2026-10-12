<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="aagx-xbzq"/><path class="of2c3hfex"/><path class="y2zq3gb5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wormhole" {...props}></Icon>
<style>
:global(.aagx-xbzq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3a2 9 0 1 0 0 18a2 9 0 1 0 0-18m6.5 4a1.5 5 0 1 0 0 10a1.5 5 0 1 0 0-10m5.5 2.5a1 2.5 0 1 0 0 5a1 2.5 0 1 0 0-5");
}

:global(.of2c3hfex) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3q7 4.75 12 6.5M4.75 21q7-4.75 12-6.5");
}

:global(.y2zq3gb5i) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
