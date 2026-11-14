<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="way8wpbnf"/><path class="gibkbob0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skier-jump" {...props}></Icon>
<style>
:global(.gibkbob0y) {
  d: path("m11.5 8l4 .75l4-1.25M11 15.25l9-3M2.5 20.5h5c2.5 0 3.75-.75 4.5-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.way8wpbnf) {
  d: path("M14.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM16 7.5L14 11l2 2.5");
}

</style>
