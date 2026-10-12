<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="c0pveubrp"/><circle class="ptricrbgn"/><path class="e4bskll8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scissors-sharp" {...props}></Icon>
<style>
:global(.c0pveubrp) {
  cx: 6px;
  cy: 6.25px;
  r: 3.25px;
}

:global(.e4bskll8f) {
  d: path("m8.6 8.2l11.65 9.3M8.6 15.8l11.65-9.3");
}

:global(.ptricrbgn) {
  cx: 6px;
  cy: 17.75px;
  r: 3.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
