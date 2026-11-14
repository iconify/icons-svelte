<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j__ejdl6m"/><path class="yvdcteb7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:side-brush" {...props}></Icon>
<style>
:global(.j__ejdl6m) {
  d: path("M11.25 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yvdcteb7g) {
  d: path("M13.75 8.5q0-4.5 6.75-5.5M16 12.25q3.75 2.25 1.25 8.5m-5.75-8.5q-3.75 2.25-8-3");
}

</style>
