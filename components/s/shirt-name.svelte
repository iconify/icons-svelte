<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bdnfiua1d"/><path class="tjx3u2hcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shirt-name" {...props}></Icon>
<style>
:global(.bdnfiua1d) {
  d: path("M8 3L2.5 6.5l2 4.5l2-1v11h11V10l2 1l2-4.5L16 3q-4 3-8 0Z");
}

:global(.tjx3u2hcm) {
  d: path("M9.25 12h5.5v3.75h-5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
