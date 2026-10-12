<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dmf78xbso"/><path class="e9gvwkbxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:studio-apartment-sharp" {...props}></Icon>
<style>
:global(.dmf78xbso) {
  d: path("M7 21.25H2.75V2.75h18.5v18.5H12.5m0 0v-5.5M7 21.25a5.5 5.5 0 0 1 5.5-5.5");
}

:global(.e9gvwkbxg) {
  d: path("M13.5 5.25h5.25v8.5H13.5zM15 7.5h2.25M13.5 9.75h5.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
