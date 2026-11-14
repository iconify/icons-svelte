<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qn982mbve"/><path class="pj0z00bom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trending" {...props}></Icon>
<style>
:global(.pj0z00bom) {
  d: path("M15.5 6.5h6v6");
}

:global(.qn982mbve) {
  d: path("M2.5 17.5L9 11l4 4l8.5-8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
