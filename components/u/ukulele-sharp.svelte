<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wn7q51bhl"/><circle class="xbakwn5ni"/><path class="mej7q9r2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ukulele-sharp" {...props}></Icon>
<style>
:global(.mej7q9r2w) {
  d: path("M10.5 18.25h3");
}

:global(.wn7q51bhl) {
  d: path("M14.4 12.94a4.5 4.5 0 1 1-4.8 0a3.25 3.25 0 1 1 4.8 0ZM12 7.5V5.25m-1.75-2.5h3.5v2.5h-3.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xbakwn5ni) {
  cx: 12px;
  cy: 13.5px;
  r: 1.5px;
}

</style>
