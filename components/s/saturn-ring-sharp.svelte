<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="pfpt48slt"/><path class="mwt9g9byc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:saturn-ring-sharp" {...props}></Icon>
<style>
:global(.mwt9g9byc) {
  d: path("M21.16 8.67a9.75 2.5-20 1 1-18.32 6.66");
}

:global(.pfpt48slt) {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
