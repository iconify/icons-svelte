<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b4n404boj"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vr-headset-clock" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.b4n404boj) {
  d: path("M5 5a2.5 2.5 0 0 1 2.5-2.5h9A2.5 2.5 0 0 1 19 5v3.5c0 2.25-1.5 3.5-3.25 3.5c-1.25 0-2.25-1.5-3.75-1.5S9.5 12 8.25 12C6.5 12 5 10.75 5 8.5ZM2 6.5h3m14 0h3M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
