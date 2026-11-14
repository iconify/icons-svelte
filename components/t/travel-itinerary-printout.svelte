<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcwosebch"/><path class="p1tpbpb4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:travel-itinerary-printout" {...props}></Icon>
<style>
:global(.hcwosebch) {
  d: path("M4 9h16v8H4Zm3.5 0V3.5h9V9");
}

:global(.p1tpbpb4s) {
  d: path("M7.5 14h9v6.5h-9Zm2.5 3h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
