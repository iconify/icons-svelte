<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ltaqp6b9m"/><path class="f-nzghbmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spacetime-curve" {...props}></Icon>
<style>
:global(.f-nzghbmo) {
  d: path("M7.5 5.5q1 6.75 0 13.5m9-13.5q-1 6.75 0 13.5M12 6v14m0-6h.01");
}

:global(.ltaqp6b9m) {
  d: path("M3 4q9 4 18 0M3 10q9 8 18 0M3 16q9 8 18 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
