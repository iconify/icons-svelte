<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gmjhnix_r"/><path class="iqxd-ni7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sensory-friendly" {...props}></Icon>
<style>
:global(.gmjhnix_r) {
  d: path("M4.5 15v-3a7.5 7.5 0 0 1 15 0v3");
}

:global(.iqxd-ni7f) {
  d: path("M3 14h4v6.5H3Zm14 0h4v6.5h-4Zm-5 4.5S9.75 17 9.75 15.25c0-1 .75-1.75 1.5-1.75c.25 0 .5.25.75.5c.25-.25.5-.5.75-.5c.75 0 1.5.75 1.5 1.75C14.25 17 12 18.5 12 18.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
