<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z9m68sbcd"/><path class="j-zv-trfl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:turn-sharp-left" {...props}></Icon>
<style>
:global(.j-zv-trfl) {
  d: path("M6.5 9.5V15H12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z9m68sbcd) {
  d: path("M17.5 20.5V4l-11 11");
}

</style>
