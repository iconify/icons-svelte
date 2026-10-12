<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zp-kn7ugk"/><path class="l268dxbvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tent-plus-sharp" {...props}></Icon>
<style>
:global(.l268dxbvv) {
  d: path("m12.24 12.21l2.52 7.33l.24.71H9l.24-.71l2.52-7.33l.24-.71zM10.5 2.75L12 4l1.5-1.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zp-kn7ugk) {
  d: path("m12.71 5.32l7.33 13.61l.71 1.32H3.25l.71-1.32l7.33-13.61L12 4z");
}

</style>
