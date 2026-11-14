<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gzc-2r5ic"/><path class="a2agztb8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sports-stream" {...props}></Icon>
<style>
:global(.a2agztb8h) {
  d: path("m10 10l5.5 3.25L10 16.5Z");
}

:global(.gzc-2r5ic) {
  d: path("M2.5 6.5h19V20h-19Zm5.5-4l4 4l4-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
