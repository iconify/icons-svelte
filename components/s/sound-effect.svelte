<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cibm8r7dz"/><rect class="kzsi2uvsl"/><path class="prtaznesx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sound-effect" {...props}></Icon>
<style>
:global(.cibm8r7dz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 6a.9.9 0 0 1 .9-.9h1.32l2.64-2.22a.54.54 0 0 1 .9.42v8.4a.54.54 0 0 1-.9.42L9.47 9.9H8.15a.9.9 0 0 1-.9-.9ZM16 5.5a3 3 0 0 1 0 4");
}

:global(.kzsi2uvsl) {
  width: 11px;
  height: 6.5px;
  x: 6.5px;
  y: 14.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.25px;
}

:global(.prtaznesx) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 18h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
