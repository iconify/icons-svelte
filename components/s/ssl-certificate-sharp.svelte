<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jl4903ezj"/><path class="yut2xo4dj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ssl-certificate-sharp" {...props}></Icon>
<style>
:global(.jl4903ezj) {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yut2xo4dj) {
  d: path("m8.5 14.73l-1.25 6.52l4.75-2.5l4.75 2.5l-1.25-6.52m-6-6.23h5v4h-5zm1 0v-3h3v3");
}

</style>
