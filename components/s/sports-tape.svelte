<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cnl-h3b9q"/><path class="euzws7l6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sports-tape" {...props}></Icon>
<style>
:global(.cnl-h3b9q) {
  d: path("M2.5 11.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

:global(.euzws7l6i) {
  d: path("M10.5 19.5h11l-2-3h-2.75M7 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
