<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ysgoz85np"/><path class="idplblmkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sputnik-sharp" {...props}></Icon>
<style>
:global(.idplblmkl) {
  d: path("M3.25 8.5a5.25 2 0 0 0 10.5 0m-.14 1.2l7.64 1.8m-9.04.71L19 19m-9.3-5.39l1.8 7.64");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ysgoz85np) {
  cx: 8.5px;
  cy: 8.5px;
  r: 5.25px;
}

</style>
