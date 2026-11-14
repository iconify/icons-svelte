<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zeg7c9oja"/><path class="ok0k_pcyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:security-camera-eye" {...props}></Icon>
<style>
:global(.ok0k_pcyh) {
  d: path("M6 12a3.5 1.75 0 1 0 7 0a3.5 1.75 0 1 0-7 0Zm3.5.25h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zeg7c9oja) {
  d: path("m1.883 10.166l13.156-4.789l3.078 8.457l-13.156 4.789ZM16.5 9.5h5m0-4v8");
}

</style>
