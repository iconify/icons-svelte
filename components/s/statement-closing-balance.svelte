<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="imi1lwbqa"/><path class="nqchmx61f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:statement-closing-balance" {...props}></Icon>
<style>
:global(.imi1lwbqa) {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8M8 10h8");
}

:global(.nqchmx61f) {
  d: path("M7 13.5h10V18H7Zm2.25 2.25h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
