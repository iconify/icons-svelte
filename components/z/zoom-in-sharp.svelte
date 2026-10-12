<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ry59zbcad"/><path class="fj3s-0b6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:zoom-in-sharp" {...props}></Icon>
<style>
:global(.fj3s-0b6o) {
  d: path("M8 11h6m-3-3v6m5.5 2.5L21 21");
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
