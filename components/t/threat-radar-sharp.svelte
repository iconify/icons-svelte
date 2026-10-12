<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vw32xbcti"/><path class="lr1yyx9sp"/><path class="zo_q_kmis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:threat-radar-sharp" {...props}></Icon>
<style>
:global(.lr1yyx9sp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5a9 9 0 0 1 9 9m-9 0l9.61-13.72");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vw32xbcti) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5V3.75A16.75 16.75 0 0 1 20.25 20.5Z");
}

:global(.zo_q_kmis) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 15.5h.01");
}

</style>
