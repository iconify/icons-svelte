<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gn9o02m8q"/><path class="fobco7e6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tabla-sharp" {...props}></Icon>
<style>
:global(.fobco7e6j) {
  d: path("M2.75 12.5a4.5 1.5 0 1 0 9 0a4.5 1.5 0 1 0-9 0Zm12-3.5a3.25 1.25 0 1 0 6.5 0a3.25 1.25 0 1 0-6.5 0Zm1 6.5h4.5");
}

:global(.gn9o02m8q) {
  d: path("M2.75 12.5a4.5 1.5 0 0 0 9 0c0 5-1.5 8.75-4.5 8.75s-4.5-3.75-4.5-8.75Zm12-3.5a3.25 1.25 0 0 0 6.5 0l-.75 11v1.25h-5V20Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
