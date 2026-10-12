<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ouu928b9k"/><path class="vktvftqbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:storage-box-sharp" {...props}></Icon>
<style>
:global(.ouu928b9k) {
  d: path("M2.75 4.25h18.5v3.5H2.75zm1.5 3.5h15.5v13.5H4.25v-2Z");
}

:global(.vktvftqbh) {
  d: path("M9 10.75h6v2.5H9z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
