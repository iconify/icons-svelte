<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ujydecw_q"/><path class="a7xbknbyy"/><path class="vje23xb_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:slider-rail-sharp" {...props}></Icon>
<style>
:global(.a7xbknbyy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01");
}

:global(.ujydecw_q) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10V10H7z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vje23xb_d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10v3.5m-9.25 0h18.5M6 18.5h12m-2-2l2 2l-2 2");
}

</style>
