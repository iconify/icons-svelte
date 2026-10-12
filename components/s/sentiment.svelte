<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="y3ta-w_yv"/><path class="z6hf7-b6q"/><path class="foyxdqbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sentiment" {...props}></Icon>
<style>
:global(.foyxdqbhs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10.25c1.1 1.2 2.9 1.2 4 0m3.75 8.5v2.5m3-5v5m3-7.5v7.5");
}

:global(.y3ta-w_yv) {
  cx: 8.25px;
  cy: 8.25px;
  r: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z6hf7-b6q) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.25h.01m3.49 0h.01");
}

</style>
