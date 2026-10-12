<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="naj80kbas"/><path class="razwvsbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:streaming-text-sharp" {...props}></Icon>
<style>
:global(.naj80kbas) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5h7m3.5 0h8m-18.5 6h4m3.25 0h11.25m-18.5 6h5.5");
}

:global(.razwvsbuw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 17.5h.01m3.74 0h.01m3.74 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
