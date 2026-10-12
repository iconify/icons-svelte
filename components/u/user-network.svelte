<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="g2orrxpuo"/><path class="dh62h9b8n"/><path class="ynqv78lsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:user-network" {...props}></Icon>
<style>
:global(.dh62h9b8n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75m13.63-12.4l1.49-2.2m-1.49 5.5l1.49 2.2");
}

:global(.g2orrxpuo) {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ynqv78lsa) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.25 4h.01M16.5 9.5h.01m3.74 5.5h.01");
}

</style>
