<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j54l-_liv"/><path class="jadrmr06b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ski-socks" {...props}></Icon>
<style>
:global(.j54l-_liv) {
  d: path("M6 2.5h7v10l5 3.5a3.25 3.25 0 0 1-3.5 5l-7-4.25A3.5 3.5 0 0 1 6 14Zm0 4h7");
}

:global(.jadrmr06b) {
  d: path("M6 11q4 1 4 7.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
