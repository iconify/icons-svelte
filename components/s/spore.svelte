<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="tp9mb1u4p"/><path class="jclsa9pnm"/><circle class="hkwurnbrq"/><circle class="c2ean4bsg"/><circle class="v78ltpbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spore" {...props}></Icon>
<style>
:global(.c2ean4bsg) {
  cx: 12px;
  cy: 4.5px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hkwurnbrq) {
  cx: 18px;
  cy: 7px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jclsa9pnm) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 13.5h.01M11 17h.01");
}

:global(.tp9mb1u4p) {
  cx: 9px;
  cy: 15px;
  r: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v78ltpbgy) {
  cx: 19.5px;
  cy: 13.5px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
