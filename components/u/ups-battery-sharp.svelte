<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kupfe8ior"/><path class="l1gzk17yp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ups-battery-sharp" {...props}></Icon>
<style>
:global(.kupfe8ior) {
  d: path("M5 2.75h14v18.5H5zm3.5 3h7");
}

:global(.l1gzk17yp) {
  d: path("m13 9.5l-3 4.25h4L11 18");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
