<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="mzpshbbyo"/><path class="ohm1l3sxk"/><circle class="gzk5d2xwl"/><path class="x1jpzin5b"/><path class="ham-4mshf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tea-infuser" {...props}></Icon>
<style>
:global(.gzk5d2xwl) {
  cx: 12px;
  cy: 15.25px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ham-4mshf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 18.25h.01m3.49 0h.01");
}

:global(.mzpshbbyo) {
  width: 4px;
  height: 3.5px;
  x: 10px;
  y: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

:global(.ohm1l3sxk) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5v2.75");
}

:global(.x1jpzin5b) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15.25h12");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
