<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctq0t5yes"/><path class="vhrqxgm1n"/><path class="mpvavabzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:subscription-expired" {...props}></Icon>
<style>
:global(.ctq0t5yes) {
  d: path("M5.938 8.5A7 7 0 0 1 19 12");
}

:global(.mpvavabzv) {
  d: path("M7.5 14.5L5 12l-2.5 2.5M10 10l4 4m0-4l-4 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vhrqxgm1n) {
  d: path("M16.5 9.5L19 12l2.5-2.5m-3.438 6A7 7 0 0 1 5 12");
}

</style>
