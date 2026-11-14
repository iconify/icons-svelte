<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aldo75bii"/><path class="kbpt6ibby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:volumetric-capture" {...props}></Icon>
<style>
:global(.aldo75bii) {
  d: path("M7 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM4 19c0-3.25 2.75-5.5 6.5-5.5q.366 0 .718.029");
}

:global(.kbpt6ibby) {
  d: path("M3 6.5a7.5 2.25 0 1 0 15 0a7.5 2.25 0 1 0-15 0ZM14 16h5.5v5H14Zm5.5 1.5L22 16v5l-2.5-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
