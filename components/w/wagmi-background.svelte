<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGYxdVQcMx)" class="r4i437pya"/><path class="jgoof5b0s"/></g><defs><linearGradient id="SVGYxdVQcMx" x1="4" x2="19.254" y1="10.922" y2="10.922" gradientUnits="userSpaceOnUse"><stop class="ffqf11p4o"/><stop offset="1" class="yctw9cc4l"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:wagmi-background" {...props}></Icon>
<style>
:global(.ffqf11p4o) {
  stop-color: var(--svg-color--dcc093, #dcc093);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jgoof5b0s) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.103 5.143H4V10.6l8 6.868l8-7.24V5.177l-8 6.663zm12.263 0L12 8.914L7.634 5.143zM20 13.668l-6.171 5.189H20zm-9.771 5.189L4 13.486v5.37z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.yctw9cc4l) {
  stop-color: var(--svg-color--c4a878, #c4a878);
}

</style>
