<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qanaiovte"/><circle class="xawnb59pb"/><path class="v7qj7f6yx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:walker-frame-sharp" {...props}></Icon>
<style>
:global(.qanaiovte) {
  d: path("m6.1 20.25l1.65-12l.219-1.516L9.5 6.75h5l1.531-.016l.219 1.516l1.5 10M7 13.25h9.5");
}

:global(.v7qj7f6yx) {
  d: path("M4.75 21.25H7.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xawnb59pb) {
  cx: 17.75px;
  cy: 19.75px;
  r: 1.5px;
}

</style>
