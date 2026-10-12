<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="pu83mmd4m"/><path class="rvf254fph"/><path class="f1814vb6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sleeping-bag" {...props}></Icon>
<style>
:global(.f1814vb6s) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.5 11.5h.01");
}

:global(.pu83mmd4m) {
  width: 11px;
  height: 18.5px;
  x: 6.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 4px;
}

:global(.rvf254fph) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.5C8.25 7.25 10 6.75 12 6.75s3.75.5 5.5 1.75m-3 3v6.75");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
