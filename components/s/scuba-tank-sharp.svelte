<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ybozgwbve"/><path class="n90lfrb0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scuba-tank-sharp" {...props}></Icon>
<style>
:global(.n90lfrb0j) {
  d: path("M13.25 4.75h5.5V10");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybozgwbve) {
  d: path("M8 7h8v14.25H8zm0 4h8m-8 6.25h8M10.75 7V4.25h2.5V7Z");
}

</style>
