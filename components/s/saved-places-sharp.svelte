<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f15a5-boe"/><path class="mtelvrbtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:saved-places-sharp" {...props}></Icon>
<style>
:global(.f15a5-boe) {
  d: path("M6.5 2.75h12.25v18.5l-1.02-.72l-4.71-3.31L12 16.5l-1.02.72l-4.71 3.31l-1.02.72V2.75z");
}

:global(.mtelvrbtc) {
  d: path("M12 13c-1.75-1.75-3-3-3-4.75a3 3 0 0 1 6 0c0 1.75-1.25 3-3 4.75Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
