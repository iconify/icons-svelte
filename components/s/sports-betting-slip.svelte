<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mg2-xhbke"/><path class="n0hh8tbst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sports-betting-slip" {...props}></Icon>
<style>
:global(.mg2-xhbke) {
  d: path("M5 2.5h14V21l-2.25-1.5L14.5 21L12 19.5L9.5 21l-2.25-1.5L5 21Z");
}

:global(.n0hh8tbst) {
  d: path("M7.75 7.25L9 8.5L11.25 6M14 7.25h2.25M7.75 12h3.5v3.5h-3.5ZM14 13.75h2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
