<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w9fyjg4yb"/><path class="zy_uced1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wok-sharp" {...props}></Icon>
<style>
:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.w9fyjg4yb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.75h15.5c0 5-3.45 8.5-7.75 8.5s-7.75-3.5-7.75-8.5ZM18 12.25l3.25-1.75");
}

:global(.zy_uced1k) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 6.75h.01M10.5 4h.01m3.24 2.75h.01");
}

</style>
