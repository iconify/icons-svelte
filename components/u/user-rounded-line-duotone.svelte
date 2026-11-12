<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><ellipse class="kdx2mdh6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-rounded-line-duotone" {...props}></Icon>
<style>
:global(.dtl23o_xq) {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdx2mdh6q) {
  cx: 12px;
  cy: 17px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 7px;
  ry: 4px;
}

</style>
