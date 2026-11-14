<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x45vy__1m"/><path class="gnpq_53wx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-efficiency-label" {...props}></Icon>
<style>
:global(.gnpq_53wx) {
  d: path("M14.5 7.5s-3 3.25-3 5.5a3 3 0 0 0 6 0c0-2.25-3-5.5-3-5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x45vy__1m) {
  d: path("m2.5 12l6-7.5h13v15h-13Z");
}

</style>
