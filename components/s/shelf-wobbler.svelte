<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oinpwu69o"/><path class="aeihrcc1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shelf-wobbler" {...props}></Icon>
<style>
:global(.aeihrcc1b) {
  d: path("M6 16.5c0-3 3-2 3-4.5c0-1.5.75-2.25 1.5-2.5m2.5-2h4m-3 2.25h2");
}

:global(.oinpwu69o) {
  d: path("M2.5 16.5h19V20h-19Zm7-9a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
