<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ru4tp72_w"/><path class="p1ykhfepk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:usp" {...props}></Icon>
<style>
:global(.p1ykhfepk) {
  d: path("m9 9l3 11.75L15 9");
}

:global(.ru4tp72_w) {
  d: path("M7 3.5h10L21.5 9L12 21L2.5 9ZM2.5 9h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
