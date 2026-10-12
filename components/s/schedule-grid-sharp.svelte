<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="aof5h9brq"/><path class="klntv9bgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:schedule-grid-sharp" {...props}></Icon>
<style>
:global(.aof5h9brq) {
  d: path("M3.25 3.25h17.5v17.5H3.25zm0 5h17.5m-12.5 0v12.5m-3-8.75h1m-1 5h1");
}

:global(.klntv9bgc) {
  d: path("M10.75 10.75h7v2.5h-7zm0 5h4.5v2.5h-4.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
