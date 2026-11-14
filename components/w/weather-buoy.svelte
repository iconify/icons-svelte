<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="maxbprbxu"/><path class="z0lkabbev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:weather-buoy" {...props}></Icon>
<style>
:global(.maxbprbxu) {
  d: path("M6.5 15a5.5 5.5 0 0 1 11 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z0lkabbev) {
  d: path("M2.5 15q2-1.5 4 0h11q2 1.5 4 0M12 9.5V3M2.5 19.5q2.375-1.5 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>
