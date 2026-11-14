<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x5sqeab5m"/><path class="jcmr5bcjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:selfie" {...props}></Icon>
<style>
:global(.jcmr5bcjh) {
  d: path("M10 10.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8.25 18.5c0-2 1.75-3 3.75-3s3.75 1 3.75 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x5sqeab5m) {
  d: path("M5.5 2.5h13v19h-13ZM12 5.25h.01");
}

</style>
