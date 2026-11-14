<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi-y5jnwu"/><path class="u31giwxbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tools-crossed" {...props}></Icon>
<style>
:global(.u31giwxbe) {
  d: path("M15.5 3.75V7A1.5 1.5 0 0 0 17 8.5h3.25M4.5 19.5L12 12m-1.061 2.475l3.536-3.536l6.01 6.011l-3.535 3.535Zm1.768-1.768l-6.01-6.01m-.884.884l1.768-1.768");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vi-y5jnwu) {
  d: path("M20.25 8.5a4.75 4.75 0 1 1-4.75-4.75");
}

</style>
