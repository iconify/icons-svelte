<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="ppbkvwc-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:width-limit-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.ppbkvwc-z) {
  d: path("M5.75 10.5v3.75l.56-.5l1.38-1.25l.56-.5l-.56-.5l-1.38-1.25l-.56-.5zm12.5 0v3.75l-.56-.5l-1.38-1.25l-.56-.5l.56-.5l1.38-1.25l.56-.5zM12 8.5v7");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
