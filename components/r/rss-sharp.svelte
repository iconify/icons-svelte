<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="sbe8-1cdf"/><path class="wft81v-mo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rss-sharp" {...props}></Icon>
<style>
:global(.sbe8-1cdf) {
  cx: 5.5px;
  cy: 18.5px;
  r: 1.25px;
}

:global(.wft81v-mo) {
  d: path("M4.25 11.25a8.5 8.5 0 0 1 8.5 8.5m-8.5-15.5a15.5 15.5 0 0 1 15.5 15.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
