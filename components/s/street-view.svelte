<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eteg9fsdz"/><path class="e0erkbbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:street-view" {...props}></Icon>
<style>
:global(.e0erkbbcq) {
  d: path("M7.5 15.5C4.5 16 3 16.9 3 18c0 1.75 4 3 9 3s9-1.25 9-3c0-1.1-1.5-2-4.5-2.5");
}

:global(.eteg9fsdz) {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.75 12.5v-5a2.75 2.75 0 0 1 5.5 0v5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
