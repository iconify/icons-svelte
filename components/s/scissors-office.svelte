<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzxe-4b_x"/><circle class="pn48gtbgw"/><circle class="e6kbp_ktm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scissors-office" {...props}></Icon>
<style>
:global(.bzxe-4b_x) {
  d: path("M7.5 3.5L12 12l4.5-8.5M8.92 15.7L12 12l3.08 3.7");
}

:global(.e6kbp_ktm) {
  cx: 17px;
  cy: 18px;
  r: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pn48gtbgw) {
  cx: 7px;
  cy: 18px;
  r: 3px;
}

</style>
