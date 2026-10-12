<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tt3jqibhp"/><circle class="n34kd4b2z"/><path class="wb_gttmmw"/><path class="bwa-9sbrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tag-location-sharp" {...props}></Icon>
<style>
:global(.bwa-9sbrs) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 18.25h.01");
}

:global(.n34kd4b2z) {
  cx: 8px;
  cy: 11px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tt3jqibhp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 20.75S2.75 16 2.75 11a5.25 5.25 0 0 1 10.5 0c0 5-5.25 9.75-5.25 9.75Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wb_gttmmw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 15.25H19l.6.8l1.05 1.4l.6.8l-.6.8l-1.05 1.4l-.6.8h-3.75v-6z");
}

</style>
