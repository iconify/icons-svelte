<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ufn8-_boh"/><path class="u0lmwrb4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:triage-black" {...props}></Icon>
<style>
:global(.u0lmwrb4s) {
  d: path("m13.25 6.5l2.75-4");
}

:global(.ufn8-_boh) {
  fill: currentColor;
  d: path("m12 4l5.5 4v11.5c0 1.1-.9 2-2 2h-7c-1.1 0-2-.9-2-2V8Zm0 2a2.25 2.25 0 0 0 0 4.5A2.25 2.25 0 0 0 12 6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
