<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="byrfn3bje"/><circle class="rzyzgqcqn"/><path class="djtcw4ybq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shalimar-garden-sharp" {...props}></Icon>
<style>
:global(.byrfn3bje) {
  d: path("M3.25 3.25h17.5v17.5H3.25zM12 5v4m0 6v4m-7-7h4m6 0h4");
}

:global(.djtcw4ybq) {
  d: path("M7.5 5.75L8.7 7.1v1.45a1.2 1.2 0 0 1-2.4 0V7.1zm9 0l1.2 1.35v1.45a1.2 1.2 0 0 1-2.4 0V7.1zm-9 8.5l1.2 1.35v1.45a1.2 1.2 0 0 1-2.4 0V15.6zm9 0l1.2 1.35v1.45a1.2 1.2 0 0 1-2.4 0V15.6z");
}

:global(.rzyzgqcqn) {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
