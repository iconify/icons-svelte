<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hj1-byekj"/><path class="wom5x5bys"/><path class="xda1ou47d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:summons-letter" {...props}></Icon>
<style>
:global(.hj1-byekj) {
  width: 14.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.wom5x5bys) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10L10 15l7.25-5m3.25-2.25v6");
}

:global(.xda1ou47d) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.5 17.25h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
