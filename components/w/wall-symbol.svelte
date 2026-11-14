<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qe97cg-lx"/><path class="e8ajb9buo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wall-symbol" {...props}></Icon>
<style>
:global(.e8ajb9buo) {
  d: path("M6.5 3v14.5H21M3 3h3.5M21 17.5V21");
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
