<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ry59zbcad"/><path class="m84dwj7zt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:search-check-sharp" {...props}></Icon>
<style>
:global(.m84dwj7zt) {
  d: path("M7.75 11V7.75H11m5.5 8.75L21 21");
}

:global(.ry59zbcad) {
  cx: 11px;
  cy: 11px;
  r: 7.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
