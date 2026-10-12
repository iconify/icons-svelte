<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y7bgmvbma"/><path class="f61izqzht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tv-box-sharp" {...props}></Icon>
<style>
:global(.f61izqzht) {
  d: path("M11 11.25v2.5l2.25-1.25Zm-2.75 5.5v2m7.5-2v2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y7bgmvbma) {
  d: path("M5.75 8.25h12.5v8.5H5.75z");
}

</style>
