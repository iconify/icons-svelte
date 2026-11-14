<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iqu0gdchd"/><path class="r2s0bbc4c"/><path class="dkx_8pbnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:thermometer-snow" {...props}></Icon>
<style>
:global(.dkx_8pbnr) {
  d: path("M6.5 2.5v9M2.75 4.75l7.5 4.5m-7.5 0l7.5-4.5");
}

:global(.iqu0gdchd) {
  d: path("M13.75 12.5v-7a3 3 0 0 1 6 0v7a5 5 0 1 1-6 0Z");
}

:global(.r2s0bbc4c) {
  fill: currentColor;
  d: path("M14.75 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
