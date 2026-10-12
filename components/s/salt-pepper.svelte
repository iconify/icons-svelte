<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ew_4hibuv"/><path class="cvw-6lmqu"/><path class="n0a8omxqi"/><path class="wl1ltbces"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:salt-pepper" {...props}></Icon>
<style>
:global(.cvw-6lmqu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.9 12.75h.01m2.69 0h.01");
}

:global(.ew_4hibuv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 21.25V12a3.5 3.5 0 0 1 7 0v9.25Z");
}

:global(.n0a8omxqi) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 21.25V10a3.5 3.5 0 0 1 7 0v11.25Z");
}

:global(.wl1ltbces) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 10.75h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
