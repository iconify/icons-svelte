<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hp9ld3byv"/><path class="v6vfl4bhi"/><path class="quwj-3b0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:subquery" {...props}></Icon>
<style>
:global(.hp9ld3byv) {
  d: path("M2.5 3.5h19v17h-19Zm0 4.5h19");
}

:global(.quwj-3b0b) {
  d: path("M13 14.75L12 16l1 1.25m3.5-2.5l1 1.25l-1 1.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v6vfl4bhi) {
  d: path("M5 10.5L7 12l-2 1.5M5 17h2.5m2.5-6.5h9.5v8H10Zm0 2.5h9.5");
}

</style>
