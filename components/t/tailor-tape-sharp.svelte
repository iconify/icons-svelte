<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ix1rbnbtt"/><path class="ukn-ncd_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tailor-tape-sharp" {...props}></Icon>
<style>
:global(.ix1rbnbtt) {
  cx: 12px;
  cy: 8px;
  r: 5.25px;
}

:global(.ukn-ncd_o) {
  d: path("M14.25 8a2.25 2.25 0 1 1-4.5 0a2.25 2.25 0 1 1 4.5 0m-11.5 7.75h18.5v5.5H2.75zm3.75 0v2m4-2v2m4-2v2m4-2v2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
