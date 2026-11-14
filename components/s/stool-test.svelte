<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zjsff-b1f"/><path class="era70gb2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stool-test" {...props}></Icon>
<style>
:global(.era70gb2s) {
  d: path("M10.5 17a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zjsff-b1f) {
  d: path("M5 9.5h14v12H5Zm-.5-5h15v5h-15Zm3.5 0v5m4-5v5m4-5v5m-4 0V15");
}

</style>
