<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ycapycn2r"/><path class="cgxw6ybly"/><path class="vtftgmtrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:selfie-frame-sharp" {...props}></Icon>
<style>
:global(.cgxw6ybly) {
  d: path("M7 6h11v7.25H6V6z");
}

:global(.vtftgmtrg) {
  d: path("M9.75 9.5L12 11.75l2.25-2.25M12 16.25v5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ycapycn2r) {
  d: path("M2.75 2.75h18.5v13.5H2.75z");
}

</style>
