<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="hwsal5q-o"/><path class="ws3khsbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sphere-sharp" {...props}></Icon>
<style>
:global(.hwsal5q-o) {
  cx: 12px;
  cy: 12px;
  r: 8px;
}

:global(.ws3khsbra) {
  d: path("M6.83 10.12a5.5 5.5 0 0 1 3.29-3.29");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
