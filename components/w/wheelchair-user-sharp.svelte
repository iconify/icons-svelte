<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="olg4f6bbi"/><path class="ard1fccgb"/><path class="a7-6__szj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wheelchair-user-sharp" {...props}></Icon>
<style>
:global(.a7-6__szj) {
  d: path("M8.38 11.33a5 5 0 1 0 5.79 4.05");
}

:global(.ard1fccgb) {
  d: path("M10.5 8.5v4.75h5.25l2 5.25h2.5m-9.75-8.25h4");
}

:global(.olg4f6bbi) {
  cx: 11px;
  cy: 4.5px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
