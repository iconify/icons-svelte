<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ukzm5uscx"/><path class="aip0rkx9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:split-cells-sharp" {...props}></Icon>
<style>
:global(.aip0rkx9y) {
  d: path("M9.5 12h-4m2-2l-2 2l2 2m7-2h4m-2-2l2 2l-2 2");
}

:global(.ukzm5uscx) {
  d: path("M2.75 4.75h18.5v14.5H2.75zm9.25 0v14.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
