<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cgk66lb9h"/><path class="k8u4bvbnt"/><circle class="ywzhblbsk"/><path class="etvx_o1hc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tax-free-sharp" {...props}></Icon>
<style>
:global(.cgk66lb9h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h12.5v16.5H3.75zM7 12.5L12 7");
}

:global(.etvx_o1hc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.53 14.53l4.94 4.94");
}

:global(.k8u4bvbnt) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 7.5h.01M11.5 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ywzhblbsk) {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
