<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zj2p4py0y"/><path class="af3t0nyrd"/><path class="z2-7z3bev"/><path class="pn5tqtb4p"/><path class="iejxo-b0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-high-broken" {...props}></Icon>
<style>
:global(.af3t0nyrd) {
  d: path("M5.33301 12.295C7.39361 10.0709 10.1707 9.09151 12.8624 9.35689");
}

:global(.iejxo-b0t) {
  d: path("M13.376 14.623C14.0924 14.8582 14.7672 15.2815 15.3337 15.8929");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pn5tqtb4p) {
  d: path("M8.66699 15.893C9.2104 15.3065 9.85347 14.8931 10.5374 14.6528");
}

:global(.z2-7z3bev) {
  d: path("M16.6309 10.624C17.3596 11.0681 18.0452 11.625 18.6659 12.2949");
}

:global(.zj2p4py0y) {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
