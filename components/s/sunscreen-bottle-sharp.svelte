<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fl656abhf"/><path class="n4x6lxblj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sunscreen-bottle-sharp" {...props}></Icon>
<style>
:global(.fl656abhf) {
  d: path("M7.25 3.75h10.5l-.17.99l-1.66 9.77l-.17.99h-7.5l-.17-.99l-1.66-9.77l-.17-.99zm2 14.75h5.5v2.75h-5.5z");
}

:global(.n4x6lxblj) {
  d: path("M13.75 10a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
