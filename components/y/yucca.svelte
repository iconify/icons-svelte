<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fpz1nu2ys"/><path class="p79pbwb0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:yucca" {...props}></Icon>
<style>
:global(.fpz1nu2ys) {
  d: path("M8 16h8l-1 5.5H9Zm4-5.5V16M4 6.5l8 4l8-4");
}

:global(.p79pbwb0f) {
  d: path("m8 2.5l4 8l4-8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
