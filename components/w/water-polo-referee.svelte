<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zlfogebiq"/><path class="r53x24b-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-polo-referee" {...props}></Icon>
<style>
:global(.r53x24b-h) {
  d: path("M6.25 10.5L11 2.75l4.5 6.5M5 20.5q2.25-1.75 4.5 0t4.5 0t4.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zlfogebiq) {
  d: path("M9 9.25h11V13h-7.25A3.75 3.75 0 1 1 9 9.25Z");
}

</style>
